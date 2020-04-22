# @mohithere/tiny

[![npm (scoped)]((https://img.shields.io/badge/npm-v1.0.0-blue))](https://www.npmjs.com/package/@mohithere/tiny)
(https://www.npmjs.com/package/@mohithere/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @mohithere/tiny
```

## Usage

```js
const tiny = require("@mohithere/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1