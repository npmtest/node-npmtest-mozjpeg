# npmtest-mozjpeg

#### basic test coverage for  mozjpeg (v4.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-mozjpeg.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mozjpeg) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mozjpeg.svg)](https://travis-ci.org/npmtest/node-npmtest-mozjpeg)

#### mozjpeg wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/mozjpeg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mozjpeg)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mozjpeg/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mozjpeg/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mozjpeg/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mozjpeg/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mozjpeg/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mozjpeg/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mozjpeg/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mozjpeg/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mozjpeg/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mozjpeg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mozjpeg/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mozjpeg/build/test-report.html](https://npmtest.github.io/node-npmtest-mozjpeg/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mozjpeg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mozjpeg/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mozjpeg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mozjpeg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mozjpeg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mozjpeg/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mozjpeg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mozjpeg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mozjpeg",
    "version": "4.1.1",
    "description": "mozjpeg wrapper that makes it seamlessly available as a local dependency",
    "license": "MIT",
    "repository": "imagemin/mozjpeg-bin",
    "author": {
        "name": "Kevin Mårtensson",
        "url": "github.com/kevva"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "bin": "cli.js",
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 100000"
    },
    "files": [
        "index.js",
        "cli.js",
        "lib"
    ],
    "keywords": [
        "jpeg",
        "jpg",
        "img",
        "image",
        "compress",
        "minify",
        "mozjpeg",
        "optimize"
    ],
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "devDependencies": {
        "bin-check": "^2.0.0",
        "compare-size": "^1.0.1",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
