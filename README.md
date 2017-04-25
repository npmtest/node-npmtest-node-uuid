# npmtest-node-uuid

#### basic test coverage for  [node-uuid (v1.4.8)](https://github.com/broofa/node-uuid)  [![npm package](https://img.shields.io/npm/v/npmtest-node-uuid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-uuid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-uuid.svg)](https://travis-ci.org/npmtest/node-npmtest-node-uuid)

#### Rigorous implementation of RFC4122 (v1 and v4) UUIDs.

[![NPM](https://nodei.co/npm/node-uuid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-uuid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-uuid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-uuid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-uuid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-uuid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-uuid/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-uuid/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-uuid/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-uuid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-uuid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-uuid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-uuid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-uuid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-uuid/build/test-report.html](https://npmtest.github.io/node-npmtest-node-uuid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-uuid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-uuid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-uuid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-uuid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-uuid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-uuid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Robert Kieffer"
    },
    "bin": {
        "uuid": "./bin/uuid"
    },
    "bugs": {
        "url": "https://github.com/broofa/node-uuid/issues"
    },
    "contributors": [
        {
            "name": "AJ ONeal"
        },
        {
            "name": "Christoph Tavan"
        }
    ],
    "dependencies": {},
    "deprecated": "Use uuid module instead",
    "description": "Rigorous implementation of RFC4122 (v1 and v4) UUIDs.",
    "devDependencies": {
        "nyc": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b040eb0923968afabf8d32fb1f17f1167fdab907",
        "tarball": "https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.8.tgz"
    },
    "gitHead": "6f0f31b997cd6bec7919223e8897454350ed820f",
    "homepage": "https://github.com/broofa/node-uuid",
    "installable": true,
    "keywords": [
        "guid",
        "rfc4122",
        "uuid"
    ],
    "lib": ".",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/broofa/node-uuid/master/LICENSE.md"
        }
    ],
    "main": "./uuid.js",
    "maintainers": [
        {
            "name": "broofa"
        },
        {
            "name": "defunctzombie"
        }
    ],
    "name": "node-uuid",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/broofa/node-uuid.git"
    },
    "scripts": {
        "coverage": "nyc npm test && nyc report",
        "test": "node test/test.js"
    },
    "url": "http://github.com/broofa/node-uuid",
    "version": "1.4.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
