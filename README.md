# SUIT CSS base

[![Build Status](https://travis-ci.org/suitcss/base.svg?branch=master)](https://travis-ci.org/suitcss/base)

Base styles for web applications. Provides a thin layer on top of
[Normalize.css](http://necolas.github.io/normalize.css/).

Read more about how to use [SUIT CSS](https://github.com/suitcss/suit).

## Installation

* [npm](https://www.npmjs.com/): `npm install suitcss-base`
* [Component(1)](http://github.com/component/component): `component install suitcss/base`
* Download: [zip](https://github.com/suitcss/base/releases/latest)

## Testing

Install [Node.js](https://nodejs.org/) (comes with npm).

```
npm install
```

To generate a build:

```
npm run build
```

To lint code with [postcss-bem-linter](https://github.com/postcss/postcss-bem-linter) and [stylelint](https://stylelint.io/):

```
npm run lint
```

To generate the testing build:

```
npm run build-test
```

Basic visual tests are in `test/index.html`.

## Browser support

* Google Chrome
* Firefox
* Safari
* Opera
* Internet Explorer 9+
