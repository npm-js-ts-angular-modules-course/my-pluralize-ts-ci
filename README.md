# my-pluralize-ts-ci

[![Build Status](https://travis-ci.org/npm-js-ts-angular-modules-course/my-pluralize-ts-ci.svg?branch=master)](https://travis-ci.org/npm-js-ts-angular-modules-course/my-pluralize-ts-ci) [![Coverage Status](https://coveralls.io/repos/github/npm-js-ts-angular-modules-course/my-pluralize-ts-ci/badge.svg?branch=master)](https://coveralls.io/github/npm-js-ts-angular-modules-course/my-pluralize-ts-ci?branch=master)

Source tutorial: https://codeburst.io/https-chidume-nnamdi-com-npm-module-in-typescript-12b3b22f0724

Training with Typescript library publish and training with Travis CI

A Node.js module that returns the plural form of any noun

## Installation 
```sh
npm install mypluralize --save
yarn add mypluralize
bower install pluralize --save
```

## Usage

### Javascript

```javascript
var pluralise = require('mypluralize');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```

### TypeScript
```typescript
import { getPlural } from 'mypluralize';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```

### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('mypluralize');
});
```

## Test 
```sh
npm run test
```