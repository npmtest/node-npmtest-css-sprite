# npmtest-css-sprite

#### basic test coverage for  [css-sprite (v0.9.9)](https://github.com/aslansky/css-sprite)  [![npm package](https://img.shields.io/npm/v/npmtest-css-sprite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-css-sprite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-css-sprite.svg)](https://travis-ci.org/npmtest/node-npmtest-css-sprite)

#### css sprite generator

[![NPM](https://nodei.co/npm/css-sprite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/css-sprite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-css-sprite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-css-sprite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-css-sprite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-css-sprite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-css-sprite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-css-sprite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-css-sprite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-css-sprite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-css-sprite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-css-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-css-sprite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-css-sprite/build/test-report.html](https://npmtest.github.io/node-npmtest-css-sprite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-css-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-css-sprite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-css-sprite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-css-sprite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-css-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-css-sprite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-css-sprite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-css-sprite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "css-sprite",
    "version": "0.9.9",
    "description": "css sprite generator",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/aslansky/css-sprite.git"
    },
    "homepage": "https://github.com/aslansky/css-sprite",
    "bugs": {
        "url": "https://github.com/aslansky/css-sprite/issues"
    },
    "author": {
        "name": "Alexander Slansky",
        "url": "http://slansky.net"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "bin": {
        "css-sprite": "./bin/cli.js"
    },
    "scripts": {
        "test": "mocha --reporter spec",
        "coveralls": "istanbul cover _mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "coverage": "istanbul cover _mocha --report html -- -R spec",
        "hint": "jshint lib/**/*.js index.js",
        "style": "jscs test/*.js lib/**/*.js index.js"
    },
    "main": "./index.js",
    "keywords": [
        "sprites",
        "sprite",
        "coordinates",
        "css",
        "scss",
        "less",
        "sass",
        "stylus",
        "gulpfriendly",
        "gruntplugin"
    ],
    "dependencies": {
        "async": "^0.9.0",
        "color": "^0.8.0",
        "cssesc": "^0.1.0",
        "graceful-fs": "^3.0.5",
        "imageinfo": "^1.0.4",
        "json2css": "^6.1.0",
        "layout": "~2.2.0",
        "lodash": "^3.3.1",
        "lwip": "0.0.6",
        "mkdirp": "^0.5.0",
        "mustache": "^1.1.0",
        "nomnom": "^1.8.1",
        "through2": "^0.6.3",
        "vinyl": "^0.4.6",
        "vinyl-fs": "1.0.0"
    },
    "devDependencies": {
        "mocha": "^2.1.0",
        "mocha-lcov-reporter": "^0.0.2",
        "coveralls": "^2.11.2",
        "istanbul": "^0.3.7",
        "should": "^5.1.0",
        "stylus": "^0.50.0",
        "node-sass": "^2.0.1",
        "less": "^2.4.0",
        "clean-css": "^3.1.4",
        "grunt": "^0.4.5"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
