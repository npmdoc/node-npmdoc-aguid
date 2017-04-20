# npmdoc-aguid

#### api documentation for  [aguid (v2.0.0)](https://github.com/dwyl/aguid)  [![npm package](https://img.shields.io/npm/v/npmdoc-aguid.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aguid) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aguid.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aguid)

#### A Standard-Compliant Globally Unique IDentifier (GUID) generator for Node.js and Browser

[![NPM](https://nodei.co/npm/aguid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aguid)

- [https://npmdoc.github.io/node-npmdoc-aguid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aguid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aguid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aguid/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aguid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aguid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "aguid",
    "version": "2.0.0",
    "description": "A Standard-Compliant Globally Unique IDentifier (GUID) generator for Node.js and Browser",
    "main": "lib/index.js",
    "scripts": {
        "test": "node ./node_modules/.bin/istanbul cover ./node_modules/tape/bin/tape ./test/*.js | node_modules/tap-spec/bin/cmd.js",
        "coverage": "./node_modules/.bin/istanbul cover ./node_modules/tape/bin/tape ./test/*.js && ./node_modules/.bin/istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "jshint": "./node_modules/jshint/bin/jshint -c .jshintrc --exclude-path .gitignore ."
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/dwyl/aguid.git"
    },
    "keywords": [
        "RFC4122",
        "GUID",
        "Generate",
        "Node",
        "Browser"
    ],
    "author": "@nelsonic <contact.nelsonic@gmail.com> (https://github.com/nelsonic)",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/dwyl/aguid/issues"
    },
    "homepage": "https://github.com/dwyl/aguid",
    "dependencies": {
        "uuid": "^3.0.1"
    },
    "devDependencies": {
        "istanbul": "^0.4.0",
        "jshint": "^2.8.0",
        "pre-commit": "1.1.2",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.2"
    },
    "engines": {
        "node": ">=4.0"
    },
    "pre-commit": [
        "jshint",
        "coverage"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
