#  [![NPM version][npm-image]][npm-url]

[Bubble Sort](http://en.wikipedia.org/wiki/Bubble_sort) implementation wth O(n^2) complexity based on [mgechev/javascript-algorithms](https://github.com/mgechev/javascript-algorithms).

## Install

```sh
$ npm install --save raso-bubblesort
```

## Usage

```js
var bubblesort = require('raso-bubblesort');

// Ascending order

bubblesort([3,4,1,5,2]);
// => [1,2,3,4,5]