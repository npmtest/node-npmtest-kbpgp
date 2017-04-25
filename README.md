# npmtest-kbpgp

#### basic test coverage for  [kbpgp (v2.0.69)](http://github.com/keybase/kbpgp)  [![npm package](https://img.shields.io/npm/v/npmtest-kbpgp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-kbpgp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-kbpgp.svg)](https://travis-ci.org/npmtest/node-npmtest-kbpgp)

#### Keybase's PGP Implementation

[![NPM](https://nodei.co/npm/kbpgp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kbpgp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-kbpgp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-kbpgp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-kbpgp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-kbpgp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-kbpgp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-kbpgp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-kbpgp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-kbpgp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-kbpgp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-kbpgp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-kbpgp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-kbpgp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-kbpgp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-kbpgp/build/test-report.html](https://npmtest.github.io/node-npmtest-kbpgp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-kbpgp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-kbpgp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kbpgp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-kbpgp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-kbpgp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maxwell Krohn"
    },
    "bugs": {
        "url": "https://github.com/keybase/kbpgp/issues"
    },
    "dependencies": {
        "bn": "^1.0.0",
        "bzip-deflate": "^1.0.0",
        "deep-equal": ">=0.2.1",
        "iced-error": ">=0.0.10",
        "iced-lock": "^1.0.2",
        "iced-runtime": "^1.0.3",
        "keybase-ecurve": "^1.0.0",
        "keybase-nacl": "^1.0.0",
        "minimist": "^1.2.0",
        "pgp-utils": ">=0.0.32",
        "purepack": ">=1.0.4",
        "triplesec": ">=3.0.19",
        "tweetnacl": "^0.13.1"
    },
    "description": "Keybase's PGP Implementation",
    "devDependencies": {
        "browserify": "^5.9.1",
        "colors": "0.6.2",
        "iced-coffee-script": "108.0.11",
        "iced-test": ">=0.0.21",
        "icsify": "^0.7.0",
        "minimist": "0.0.8",
        "optimist": "0.6.1",
        "uglify-js": "^2.4.13"
    },
    "directories": {
        "lib": "lib/"
    },
    "dist": {
        "shasum": "2510b4a6a07b1fbf3583017e6caeab59c415ffdc",
        "tarball": "https://registry.npmjs.org/kbpgp/-/kbpgp-2.0.69.tgz"
    },
    "gitHead": "66b9bf38b0eac2d243cbfd252813c8ab6f33e333",
    "homepage": "http://github.com/keybase/kbpgp",
    "keywords": [
        "crypto",
        "pgp",
        "keybase"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib/main.js",
    "maintainers": [
        {
            "name": "maxtaco"
        },
        {
            "name": "oconnor663"
        },
        {
            "name": "sidnicious"
        }
    ],
    "name": "kbpgp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/keybase/kbpgp.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "2.0.69",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
