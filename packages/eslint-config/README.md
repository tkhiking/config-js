# eslint-config

[![npm version](https://badge.fury.io/js/%40tkhiking%2Feslint-config.svg)](https://badge.fury.io/js/%40tkhiking%2Feslint-config)

## Installation

With npm:

```shell
npm install --save-dev eslint @tkhiking/eslint-config
npm install --save-dev prettier @tkhiking/prettier-config
npm install --save-dev typescript
```

With yarn:

```shell
yarn add --dev eslint @tkhiking/eslint-config
yarn add --dev prettier @tkhiking/prettier-config
yarn add --dev typescript
```

## Usage

Edit `package.json`:

```json
{
  "name": "your-cool-library",
  "version": "0.1.0",
  "eslintConfig": {
    "extends": "@tkhiking"
  }
}
```

Or `eslintrc.js`:

```javascript
module.exports = {
  extends: '@tkhiking',
};
```

## Related projects

- [prettier-config](https://github.com/tkhiking/config-js/packages/prettier-config)

## License

This project is licensed under the terms of the MIT license.

Copyright (c) 2020 tkhiking.