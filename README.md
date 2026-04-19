<div align="center">
    <h1>npm-module-template</h1>
    <p>
        <a href="https://voctal.dev/discord"><img src="https://img.shields.io/discord/1336303640725553213?color=5865F2&logo=discord&logoColor=white" alt="Discord server" /></a>
        <!-- <a href="https://www.npmjs.com/package/@voctal/template"><img src="https://img.shields.io/npm/v/@voctal/template.svg?maxAge=3600" alt="npm version" /></a> -->
        <!-- <a href="https://www.npmjs.com/package/@voctal/template"><img src="https://img.shields.io/npm/dt/@voctal/template.svg?maxAge=3600" alt="npm downloads" /></a> -->
        <a href="https://github.com/voctal/npm-module-template/commits/main"><img alt="Last commit" src="https://img.shields.io/github/last-commit/voctal/npm-module-template?logo=github&logoColor=ffffff" /></a>
    </p>
</div>

## About

This repository is a template to build a modern npm module in TypeScript.
This is the template we use for our modules at [Voctal](https://www.npmjs.com/~voctal).

## Features

- Bundles the module for both CJS and ESM formats
- Supports tree-shaking
- Generates source maps (`.map`) and TypeScript declaration files (`d.ts`)
- Uses the fastest linter: [Oxlint](https://oxc.rs/docs/guide/usage/linter.html)
- Uses the fastest formatter: [Oxfmt](https://oxc.rs/docs/guide/usage/formatter.html)
- Uses one of the fastest bundler: [tsdown](https://tsdown.dev/), powered by the [Rolldown](https://rolldown.rs)
- Uses [typescript-go](https://github.com/microsoft/typescript-go) for type checking and type-aware linting
- Automated publishing with a [GitHub Actions](https://github.com/features/actions) workflow, including [npm provenance](https://github.blog/security/supply-chain-security/introducing-npm-package-provenance)

## How to use

Format all files

```sh
npm run fmt
```

Type check and lint all files

```sh
npm run lint
```

Build the module

```sh
npm run build
```

You will also need to set the `NPM_TOKEN` secret on Github Actions.

## Links

- [Discord server](https://voctal.dev/discord)
- [Voctal](https://voctal.dev)
