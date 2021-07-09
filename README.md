# @mt816/eslint-config
A ESLint rule set

## Installation
```
npm install --save-dev eslint @mt816/eslint-config
```

## Usage

### 1. Install eslint and @mt816/eslint-config

```
npm install --save-dev eslint @mt816/eslint-config
```

### 2. Put it into your .eslintrc.js

- JavaScript
```
module.exports = {
  extends: ['@mt816/eslint-config'],
}
```
- TypeScript
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/typescript'],
}
```
- React
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/react'],
}
```
- React + TypeScript
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/react-typescript'],
}
```
- Vue
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/vue'],
}
```
- Vue + TypeScript
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/vue-typescript'],
}
```
- Next.js
```
module.exports = {
  extends: ['@mt816/eslint-config/presets/next'],
}
```
### 3. Put it into your package.json
```
"scripts": {
  ...
  "lint": "eslint './src/**/*.○○'",
  "lint:fix": "eslint --fix './src/**/*.○○'"
}
```

## Run
```
npm run lint
npm run lint:fix
```