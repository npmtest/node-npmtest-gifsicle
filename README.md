# npmtest-gifsicle

#### basic test coverage for  [gifsicle (v3.0.4)](https://github.com/imagemin/gifsicle-bin#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gifsicle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gifsicle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gifsicle.svg)](https://travis-ci.org/npmtest/node-npmtest-gifsicle)

#### gifsicle wrapper that makes it seamlessly available as a local dependency

[![NPM](https://nodei.co/npm/gifsicle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gifsicle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gifsicle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gifsicle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gifsicle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gifsicle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gifsicle/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-gifsicle/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-gifsicle/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gifsicle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gifsicle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gifsicle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gifsicle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gifsicle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gifsicle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gifsicle/build/test-report.html](https://npmtest.github.io/node-npmtest-gifsicle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gifsicle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gifsicle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gifsicle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gifsicle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gifsicle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gifsicle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gifsicle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gifsicle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin Martensson",
        "url": "github.com/kevva"
    },
    "bin": {
        "gifsicle": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/imagemin/gifsicle-bin/issues"
    },
    "dependencies": {
        "bin-build": "^2.0.0",
        "bin-wrapper": "^3.0.0",
        "logalot": "^2.0.0"
    },
    "description": "gifsicle wrapper that makes it seamlessly available as a local dependency",
    "devDependencies": {
        "bin-check": "^2.0.0",
        "compare-size": "^1.0.0",
        "mkdirp": "^0.5.0",
        "mocha": "^2.2.4",
        "rimraf": "^2.3.2",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f45cb5ed10165b665dc929e0e9328b6c821dfa3b",
        "tarball": "https://registry.npmjs.org/gifsicle/-/gifsicle-3.0.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "cli.js",
        "lib"
    ],
    "gitHead": "88b8b2d536749d484c6d5a2fb5cf5f3756138864",
    "homepage": "https://github.com/imagemin/gifsicle-bin#readme",
    "keywords": [
        "gif",
        "img",
        "image",
        "compress",
        "minify",
        "optimize"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "shinnn"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "gifsicle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/imagemin/gifsicle-bin.git"
    },
    "scripts": {
        "postinstall": "node lib/install.js",
        "test": "xo && mocha --timeout 50000"
    },
    "version": "3.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
