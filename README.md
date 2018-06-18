# vcx-tsconfig
Base TSConfig configuration for Vicinity Projects using TypeScript.

## Install
NPM
```sh
npm install @vicinity/tsconfig --save-dev
```
Yarn
```sh
yarn add @vicinity/tsconfig -D
```

## Use
In your own typescript project, simply extend your `tsconfig.json` from this one.
```json
{
  "extends": "./node_modules/@vicinity/vcx-tsconfig/tsconfig.json"
}
```