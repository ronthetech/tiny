![npm](https://img.shields.io/npm/v/@ronjtech/tiny)
![npm bundle size](https://img.shields.io/bundlephobia/min/@ronjtech/tiny)
[![install size](https://packagephobia.com/badge?p=@ronjtech/tiny)](https://packagephobia.com/result?p=@ronjtech/tiny)

Remove all spaces from a string.

# Install

```shell
npm install @ronjtech/tiny
```

# Usage

```javascript
const tiny = require("@ronjtech/tiny");

tiny("There's a lot of space here!");
//-> "There'salotofspacehere!"

tiny(1234);
//-> Uncaught TypeError: Tiny needs a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
