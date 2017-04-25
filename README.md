# npmtest-detector

#### basic test coverage for  [detector (v2.5.0)](http://spmjs.io/docs/detector/)  [![npm package](https://img.shields.io/npm/v/npmtest-detector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-detector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-detector.svg)](https://travis-ci.org/npmtest/node-npmtest-detector)

#### The module for detect client-side information.

[![NPM](https://nodei.co/npm/detector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/detector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-detector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-detector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-detector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-detector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-detector/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-detector/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-detector/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-detector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-detector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-detector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-detector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-detector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-detector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-detector/build/test-report.html](https://npmtest.github.io/node-npmtest-detector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-detector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-detector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-detector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-detector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-detector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-detector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-detector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-detector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "冒顿"
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-0"
        ],
        "plugins": [
            "add-module-exports"
        ]
    },
    "bin": {
        "detector": "./bin/detector"
    },
    "browser": "./web/web-detector.js",
    "bugs": {
        "url": "https://github.com/hotoo/detector/issues"
    },
    "dependencies": {
        "colors": "0.6.2",
        "commander": "~1.1.1"
    },
    "description": "The module for detect client-side information.",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-stage-0": "^6.5.0",
        "eslint": "~1.4.3",
        "expect.js": "0.3.1",
        "istanbul": "^0.3.22",
        "mocha": "^2.3.3",
        "spm": "~3.6.12"
    },
    "directories": {},
    "dist": {
        "shasum": "7ecbe84cd667c1cbe19fc74f4e516dcc8bde4f6d",
        "tarball": "https://registry.npmjs.org/detector/-/detector-2.5.0.tgz"
    },
    "files": [
        "lib",
        "bin",
        "web",
        "package.json",
        "README.md",
        "README-zh_CN.md"
    ],
    "gitHead": "dc5ada4d7f566819d3d12a266926243b09d682a6",
    "homepage": "http://spmjs.io/docs/detector/",
    "keywords": [
        "utility",
        "userAgent",
        "arale",
        "Browser",
        "OS",
        "Operation System",
        "Device",
        "Rendering Engine"
    ],
    "license": "MIT",
    "main": "./lib/node-detector.js",
    "maintainers": [
        {
            "name": "hotoo"
        }
    ],
    "name": "detector",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hotoo/detector.git"
    },
    "scripts": {
        "build": "rm -rf web/* && babel ./lib --out-dir ./web/ --ignore node-detector.js && rm ./web/rules.js",
        "prepublish": "npm run build",
        "test": "make test"
    },
    "spm": {
        "main": "./lib/web-detector.js",
        "devDependencies": {
            "jquery": "1.7.2",
            "expect.js": "0.3.1"
        },
        "tests": "tests/*-spec.js",
        "build": {
            "babel": {}
        }
    },
    "version": "2.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
