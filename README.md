# Eslint Config

![npm](https://img.shields.io/npm/dt/@repeale/eslint-config?style=flat-square)

- [Prettier Config](#eslint-config)
  - [Getting started](#getting-started)
  - [Configs](#configs)
  - [License](#license)

## Getting started

Install the package and related peerDependencies as `devDependencies`:

```sh
npm install --save-dev @repeale/eslint-config @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint prettier typescript
```

or

```sh
yarn add --dev @repeale/eslint-config @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint-config-prettier eslint-plugin-prettier eslint-plugin-react eslint prettier typescript
```

Extend `@repeale/eslint-config` in your `.eslintrc` file with one of the available configurations:

```json
{
  "extends": "@repeale/eslint-config/react-ts-prettier"
}
```

## Configs

- @repeale/eslint-config/react-ts-prettier

## License

[MIT License](./LICENSE)
