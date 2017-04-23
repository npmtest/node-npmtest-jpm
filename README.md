# npmtest-jpm

#### basic test coverage for  [jpm (v1.3.1)](https://github.com/mozilla-jetpack/jpm)  [![npm package](https://img.shields.io/npm/v/npmtest-jpm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jpm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jpm.svg)](https://travis-ci.org/npmtest/node-npmtest-jpm)

#### Jetpack Mechanic utilities for creating, testing, running and packaging Mozilla Jetpack Addons

[![NPM](https://nodei.co/npm/jpm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jpm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jpm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jpm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jpm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jpm/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jpm/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jpm/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jpm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jpm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jpm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jpm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jpm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jpm/build/test-report.html](https://npmtest.github.io/node-npmtest-jpm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jpm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jpm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jpm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jpm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jpm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jpm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jpm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jordan Santell"
    },
    "bin": {
        "jpm": "./bin/jpm"
    },
    "bugs": {
        "url": "http://github.com/mozilla-jetpack/jpm/issues"
    },
    "dependencies": {
        "commander": "2.9.0",
        "decompress-zip": "0.3.0",
        "firefox-profile": "0.4.0",
        "fs-extra": "0.30.0",
        "fs-promise": "0.3.1",
        "fx-runner": "1.0.5",
        "jetpack-id": "0.0.4",
        "jetpack-validation": "0.0.7",
        "jpm-core": "0.0.11",
        "jsontoxml": "0.0.11",
        "jszip": "2.4.0",
        "lodash": "4.11.1",
        "minimatch": "3.0.2",
        "mozilla-toolkit-versioning": "0.0.2",
        "mozilla-version-comparator": "1.0.2",
        "node-watch": "0.3.4",
        "object-assign": "4.1.0",
        "open": "0.0.5",
        "promzard": "0.3.0",
        "read": "1.0.7",
        "semver": "5.1.0",
        "sign-addon": "0.2.0",
        "tmp": "0.0.28",
        "when": "3.7.2",
        "xml2js": "0.4.16",
        "zip-dir": "1.0.2"
    },
    "description": "Jetpack Mechanic utilities for creating, testing, running and packaging Mozilla Jetpack Addons",
    "devDependencies": {
        "async": "1.5.0",
        "chai": "3.4.1",
        "conventional-changelog-cli": "1.2.0",
        "conventional-changelog-lint": "1.0.0",
        "dive": "0.4.0",
        "eslint": "3.5.0",
        "eslint-plugin-dependencies": "1.3.0",
        "get-firefox": "1.5.0",
        "glob": "5.0.3",
        "husky": "^0.10.1",
        "mocha": "2.5.3",
        "release-it": "2.3.1",
        "rimraf": "2.3.2",
        "teacher": "0.0.1",
        "xmldom": "0.1.19"
    },
    "directories": {},
    "dist": {
        "shasum": "430c98193e87692f9ccd72f6cb348eaf224dfe15",
        "tarball": "https://registry.npmjs.org/jpm/-/jpm-1.3.1.tgz"
    },
    "engines": {
        "node": ">=0.10",
        "npm": ">=3.0.0"
    },
    "gitHead": "dc1aefbf7f3ea00e6c7b3030cd4c86f489484187",
    "homepage": "https://github.com/mozilla-jetpack/jpm",
    "keywords": [
        "firefox",
        "mozilla",
        "jetpack",
        "jpm"
    ],
    "license": "MPL-2.0",
    "locales": {
        "es": {
            "description": "Utilidades Mecánico Jetpack para crear, probar, ejecutar y empacar Mozilla Jetpack Addons"
        }
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "addons-robot"
        },
        {
            "name": "bwinton"
        },
        {
            "name": "gozala"
        },
        {
            "name": "jsantell"
        },
        {
            "name": "kumar303"
        },
        {
            "name": "mossop"
        }
    ],
    "name": "jpm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mozilla-jetpack/jpm.git"
    },
    "scripts": {
        "addon_runners": "node ./test/run.js addon_runners",
        "addons": "node ./test/run.js addons",
        "changelog": "conventional-changelog -p angular -u",
        "changelog-lint": "conventional-changelog-lint --from master",
        "documentation": "mocha -t 5000 test/documentation",
        "functional": "node ./test/run.js functional",
        "get-unbranded-firefox": "get-firefox -ecb unbranded-release",
        "lint": "eslint bin/jpm lib test",
        "prepush": "npm run lint && npm run documentation",
        "test": "node ./test/run.js",
        "unit": "node ./test/run.js unit"
    },
    "version": "1.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
