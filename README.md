# Math.imul <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.imul` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @zibuthe7j11/ducimus-labore-occaecati
```

## Usage/Examples

```js
console.log(Math.imul(2, 4)); // 8
console.log(Math.imul(-1, 8)); // -8
console.log(Math.imul(-2, -2)); // 4
console.log(Math.imul(0xffffffff, 5)); // -5
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zibuthe7j11/ducimus-labore-occaecati
[npm-version-svg]: https://versionbadg.es/zibuthe7j11/ducimus-labore-occaecati.svg
[deps-svg]: https://david-dm.org/zibuthe7j11/ducimus-labore-occaecati.svg
[deps-url]: https://david-dm.org/zibuthe7j11/ducimus-labore-occaecati
[dev-deps-svg]: https://david-dm.org/zibuthe7j11/ducimus-labore-occaecati/dev-status.svg
[dev-deps-url]: https://david-dm.org/zibuthe7j11/ducimus-labore-occaecati#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zibuthe7j11/ducimus-labore-occaecati.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zibuthe7j11/ducimus-labore-occaecati.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zibuthe7j11/ducimus-labore-occaecati.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zibuthe7j11/ducimus-labore-occaecati
[codecov-image]: https://codecov.io/gh/zibuthe7j11/ducimus-labore-occaecati/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/zibuthe7j11/ducimus-labore-occaecati/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/zibuthe7j11/ducimus-labore-occaecati
[actions-url]: https://github.com/zibuthe7j11/ducimus-labore-occaecati/actions
