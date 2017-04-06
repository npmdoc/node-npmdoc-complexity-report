# api documentation for  [complexity-report (v1.4.1)](https://github.com/philbooth/complexity-report)  [![npm package](https://img.shields.io/npm/v/npmdoc-complexity-report.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-complexity-report) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-complexity-report.svg)](https://travis-ci.org/npmdoc/node-npmdoc-complexity-report)
#### Software complexity analysis for JavaScript projects

[![NPM](https://nodei.co/npm/complexity-report.png?downloads=true)](https://www.npmjs.com/package/complexity-report)

[![apidoc](https://npmdoc.github.io/node-npmdoc-complexity-report/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-complexity-report_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-complexity-report/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-complexity-report/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-complexity-report/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Phil Booth",
        "email": "pmbooth@gmail.com"
    },
    "bin": {
        "cr": "./src/index.js"
    },
    "bugs": {
        "url": "https://github.com/philbooth/complexity-report/issues"
    },
    "contributors": [
        {
            "name": "Phil Booth",
            "email": "pmbooth@gmail.com",
            "url": "https://github.com/philbooth"
        },
        {
            "name": "Juzer Ali",
            "url": "https://github.com/juzerali"
        },
        {
            "name": "Mark Trostler",
            "url": "https://github.com/zzo"
        },
        {
            "name": "Wyatt Preul",
            "url": "https://github.com/wpreul"
        },
        {
            "name": "Rowan Manning",
            "url": "https://github.com/rowanmanning"
        },
        {
            "name": "Andrew Pennebaker",
            "url": "https://github.com/mcandre"
        },
        {
            "name": "Nils Kenneweg",
            "url": "https://github.com/nkenneweg"
        },
        {
            "name": "Eric Burin des Roziers",
            "url": "https://github.com/Ericbdr"
        },
        {
            "name": "Matt Field",
            "url": "https://github.com/mattfield"
        },
        {
            "name": "Addison Higham",
            "url": "https://github.com/addisonj"
        },
        {
            "name": "Daniel Kavassy",
            "url": "https://github.com/dkavassy"
        }
    ],
    "dependencies": {
        "async": "^0.9.0",
        "check-types": "2.1.x",
        "commander": "2.0.x",
        "escomplex": "1.2.x",
        "escomplex-coffee": "0.3.x",
        "escomplex-js": "1.2.x"
    },
    "description": "Software complexity analysis for JavaScript projects",
    "devDependencies": {
        "chai": "1.8.x",
        "jshint": "2.1.x",
        "mocha": "1.13.x"
    },
    "directories": {},
    "dist": {
        "shasum": "2d8416787ee128a0dbe57f3badd255442d094779",
        "tarball": "https://registry.npmjs.org/complexity-report/-/complexity-report-1.4.1.tgz"
    },
    "gitHead": "bcd3325a93d28dee2ed1461fdf9b208087690e23",
    "homepage": "https://github.com/philbooth/complexity-report",
    "keywords": [
        "complexity",
        "simplicity",
        "cyclomatic",
        "halstead",
        "maintainability",
        "static",
        "analysis",
        "metrics",
        "escomplex"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "philbooth",
            "email": "pmbooth@gmail.com"
        },
        {
            "name": "addisonj",
            "email": "addisonj@gmail.com"
        }
    ],
    "name": "complexity-report",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/philbooth/complexity-report.git"
    },
    "scripts": {
        "lint": "./node_modules/jshint/bin/jshint src --config config/jshint.json",
        "test": "./node_modules/mocha/bin/mocha --ui tdd --reporter spec --colors test"
    },
    "version": "1.4.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module complexity-report](#apidoc.module.complexity-report)



# <a name="apidoc.module.complexity-report"></a>[module complexity-report](#apidoc.module.complexity-report)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
