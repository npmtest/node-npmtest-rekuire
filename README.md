# npmtest-rekuire

#### test coverage for  [rekuire (v0.1.9)](https://github.com/nadav-dav/rekuire)  [![npm package](https://img.shields.io/npm/v/npmtest-rekuire.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rekuire) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rekuire.svg)](https://travis-ci.org/npmtest/node-npmtest-rekuire)

#### 'rekuire' is basically node's 'require' without the relative paths

[![NPM](https://nodei.co/npm/rekuire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rekuire)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rekuire/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rekuire/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rekuire/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rekuire/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rekuire/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rekuire/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rekuire/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rekuire/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rekuire/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rekuire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rekuire/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rekuire/build/test-report.html](https://npmtest.github.io/node-npmtest-rekuire/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rekuire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rekuire/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rekuire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rekuire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rekuire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rekuire/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rekuire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rekuire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nadav Dav"
    },
    "bugs": {
        "url": "https://github.com/nadav-dav/rekuire/issues"
    },
    "dependencies": {
        "underscore": "^1.7.0"
    },
    "description": "'rekuire' is basically node's 'require' without the relative paths",
    "devDependencies": {
        "fs-extra": "^0.12.0",
        "jasmine-node": "^1.14.5",
        "proxyquire": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "417d9c97f474fa92fc154b6d889b5daefb4e2190",
        "tarball": "https://registry.npmjs.org/rekuire/-/rekuire-0.1.9.tgz"
    },
    "gitHead": "2db8393c6469e08f7d9f114deebf34dc3a7332fc",
    "homepage": "https://github.com/nadav-dav/rekuire",
    "keywords": [
        "require",
        "rekuire",
        "relative",
        "path",
        "node"
    ],
    "license": "BSD",
    "main": "./lib/main.js",
    "maintainers": [
        {
            "name": "nadav-dav"
        }
    ],
    "name": "rekuire",
    "optionalDependencies": {},
    "rekuire": {
        "ignore": [
            "test/testResources/ignored-by-package-json"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nadav-dav/rekuire.git"
    },
    "scripts": {
        "test": "npm install && ./node_modules/.bin/jasmine-node ./test/"
    },
    "version": "0.1.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
