# prettier-config

npm package of prettier config

---

## Install

```bash

npm install --dev @yogeshkotadiya/prettier-config

or

yarn add -D @yogeshkotadiya/prettier-config
```

---

## Configuration

```json
{
  "printWidth": 80,
  "tabWidth": 2,
  "trailingComma": "es5",
  "singleQuote": false,
  "semi": true,
  "bracketSpacing": true,
  "jsxBracketSameLine": false,
  "endOfLine": "lf"
}
```
---

## Usage

In your `.prettierrc.js` file

```js
module.exports = {
  ...require("@yogeshkotadiya/prettier-config"),
  tabWidth: 4
  //Extend or overwrite with your own preferable options
}
```

---

Author

[Yogesh Kotadiya](https://github.com/yogeshkotadiya)
