# Invincible

A series of miscellaneous functional JavaScript utility library.

[![Travis branch](https://img.shields.io/travis/chikara-chan/invincible/master.svg)](https://travis-ci.org/chikara-chan/invincible)
[![Coveralls branch](https://img.shields.io/coveralls/chikara-chan/invincible/master.svg)](https://coveralls.io/github/chikara-chan/invincible)
[![npm](https://img.shields.io/npm/v/invincible.svg)](https://www.npmjs.com/package/invincible)
[![npm](https://img.shields.io/npm/l/invincible.svg)](https://github.com/chikara-chan/invincible/blob/master/LICENSE)

## Install

``` bash
$ npm install --save invincible
# Or
$ yarn add invincible
```

## Usage

``` js
const invincible = require('invincible')
// Or
import invincible from 'invincible'
// Or
import {subModule, ...others} from 'invincible'
// Or
import subModule from 'invincible/lib/subModule'
```

## API

This library documents is published at [GitHub Pages](https://chikara-chan.github.io/invincible/). Go to the site to see more details.

## Third Support

Supports [babel-plugin-import](https://github.com/ant-design/babel-plugin-import) for loading modules on demand.

``` json
// .babelrc
{
  "plugins": [
    ["import", {
      "libraryName": "invincible",
      "camel2DashComponentName": false
    }]
  ]
}
```

``` js
import {subModule, ...others} from 'invincible'
```

Alternatively, using webpack 2 feature [tree-shaking](https://webpack.js.org/guides/tree-shaking/).

``` js
import {subModule, ...others} from 'invincible'
```

## Links
[https://chikara-chan.github.io/invincible/](https://chikara-chan.github.io/invincible/)

## License

Released under the [MIT](https://github.com/chikara-chan/invincible/blob/master/LICENSE) license.
