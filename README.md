# @wemnyelezxnpm/veritatis-necessitatibus-facere <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@wemnyelezxnpm/veritatis-necessitatibus-facere');
const Eval = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/eval');
const Range = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/range');
const Ref = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/ref');
const Syntax = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/syntax');
const Type = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/type');
const URI = require('@wemnyelezxnpm/veritatis-necessitatibus-facere/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@wemnyelezxnpm/veritatis-necessitatibus-facere
[npm-version-svg]: https://versionbadg.es/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere.svg
[deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere.svg
[deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere
[dev-deps-svg]: https://david-dm.org/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@wemnyelezxnpm/veritatis-necessitatibus-facere.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@wemnyelezxnpm/veritatis-necessitatibus-facere.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@wemnyelezxnpm/veritatis-necessitatibus-facere.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@wemnyelezxnpm/veritatis-necessitatibus-facere
[codecov-image]: https://codecov.io/gh/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@wemnyelezxnpm/veritatis-necessitatibus-facere
[actions-url]: https://github.com/wemnyelezxnpm/veritatis-necessitatibus-facere/actions
