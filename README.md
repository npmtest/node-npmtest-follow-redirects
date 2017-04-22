# npmtest-follow-redirects

#### basic test coverage for  [follow-redirects (v1.2.3)](https://github.com/olalonde/follow-redirects)  [![npm package](https://img.shields.io/npm/v/npmtest-follow-redirects.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-follow-redirects) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-follow-redirects.svg)](https://travis-ci.org/npmtest/node-npmtest-follow-redirects)

#### HTTP and HTTPS modules that follow redirects.

[![NPM](https://nodei.co/npm/follow-redirects.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/follow-redirects)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-follow-redirects/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-follow-redirects/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-follow-redirects/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-follow-redirects/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-follow-redirects/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-follow-redirects/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-follow-redirects/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-follow-redirects/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-follow-redirects/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-follow-redirects/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-follow-redirects/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-follow-redirects/build/test-report.html](https://npmtest.github.io/node-npmtest-follow-redirects/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-follow-redirects/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-follow-redirects/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-follow-redirects/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-follow-redirects/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-follow-redirects/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-follow-redirects/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-follow-redirects/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-follow-redirects/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Olivier Lalonde",
        "url": "http://www.syskall.com"
    },
    "bugs": {
        "url": "https://github.com/olalonde/follow-redirects/issues"
    },
    "contributors": [
        {
            "name": "James Talmage"
        },
        {
            "name": "Ruben Verborgh",
            "url": "https://ruben.verborgh.org/"
        }
    ],
    "dependencies": {
        "debug": "^2.4.5"
    },
    "description": "HTTP and HTTPS modules that follow redirects.",
    "devDependencies": {
        "bluebird": "^3.4.0",
        "concat-stream": "^1.5.2",
        "coveralls": "^2.11.15",
        "express": "^4.13.0",
        "mocha": "^3.2.0",
        "nyc": "^10.0.0",
        "xo": "^0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "01abaeca85e3609837d9fcda3167a7e42fdaca21",
        "tarball": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.2.3.tgz"
    },
    "files": [
        "index.js",
        "create.js",
        "http.js",
        "https.js"
    ],
    "gitHead": "ad35f4c9ab0c3fbf23c8486ba5e241d08d6b39b4",
    "homepage": "https://github.com/olalonde/follow-redirects",
    "keywords": [
        "http",
        "https",
        "url",
        "redirect",
        "client",
        "location",
        "utility"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jamestalmage"
        },
        {
            "name": "olalonde"
        },
        {
            "name": "rubenverborgh"
        }
    ],
    "name": "follow-redirects",
    "nyc": {
        "reporter": [
            "lcov",
            "text"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/olalonde/follow-redirects.git"
    },
    "scripts": {
        "test": "xo && BLUEBIRD_DEBUG=1 nyc mocha"
    },
    "version": "1.2.3",
    "xo": {
        "envs": [
            "mocha"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
