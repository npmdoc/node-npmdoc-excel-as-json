# npmdoc-excel-as-json

#### basic api documentation for  [excel-as-json (v2.0.0)](https://github.com/stevetarver/excel-as-json)  [![npm package](https://img.shields.io/npm/v/npmdoc-excel-as-json.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-excel-as-json) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-excel-as-json.svg)](https://travis-ci.org/npmdoc/node-npmdoc-excel-as-json)

#### Convert Excel data to JSON

[![NPM](https://nodei.co/npm/excel-as-json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/excel-as-json)

- [https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-excel-as-json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Tarver"
    },
    "bugs": {
        "url": "https://github.com/stevetarver/excel-as-json/issues"
    },
    "dependencies": {
        "excel": "0.1.7"
    },
    "description": "Convert Excel data to JSON",
    "devDependencies": {
        "chai": "3.5.0",
        "codecov.io": "0.1.6",
        "coffee-coverage": "1.0.1",
        "coffee-script": "1.10.0",
        "coveralls": "2.11.9",
        "istanbul": "0.4.3",
        "mocha": "2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "eb91893003f6d4965182556c47397ed63c5ee2f5",
        "tarball": "https://registry.npmjs.org/excel-as-json/-/excel-as-json-2.0.0.tgz"
    },
    "gitHead": "38fc768ac3a9cdc6e270061ff43a56ec1712bd9f",
    "homepage": "https://github.com/stevetarver/excel-as-json",
    "keywords": [
        "Excel",
        "JSON",
        "convert"
    ],
    "license": "MIT",
    "main": "lib/excel-as-json.js",
    "maintainers": [
        {
            "name": "starver"
        }
    ],
    "name": "excel-as-json",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stevetarver/excel-as-json.git"
    },
    "scripts": {
        "build": "tools/build.sh",
        "clean": "tools/clean.sh",
        "codecov": "cat ./coverage/lcov.info | ./node_modules/.bin/codecov",
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "dist": "tools/dist.sh",
        "prepublish": "tools/dist.sh",
        "test": "tools/test.sh"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
