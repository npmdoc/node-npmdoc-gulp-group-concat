# npmdoc-gulp-group-concat

#### api documentation for  gulp-group-concat (v1.1.5)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-group-concat.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-group-concat) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-group-concat.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-group-concat)

#### Concats groups of files into a smaller number of files

[![NPM](https://nodei.co/npm/gulp-group-concat.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-group-concat)

- [https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-group-concat/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-group-concat",
    "version": "1.1.5",
    "description": "Concats groups of files into a smaller number of files",
    "main": "index.js",
    "repository": "http://github.com/TakenPilot/gulp-group-concat.git",
    "scripts": {
        "test": "./node_modules/.bin/mocha -r blanket -R mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js"
    },
    "config": {
        "blanket": {
            "pattern": "index.js",
            "data-cover-never": "node_modules"
        }
    },
    "keywords": [
        "gulp",
        "gulpplugin",
        "gulpfriendly",
        "concat",
        "group",
        "filter",
        "sourcemaps",
        "multi",
        "pipe",
        "stream"
    ],
    "author": "Dane Stuckel",
    "license": "ISC",
    "dependencies": {
        "concat-with-sourcemaps": "^1.0.0",
        "globule": "^0.2.0",
        "gulp-util": "^3.0.3",
        "lodash": "^3.2.0",
        "through2": "^0.6.3",
        "vinyl-sourcemaps-apply": "^0.1.4"
    },
    "devDependencies": {
        "blanket": "^1.1.6",
        "chai": "^2.0.0",
        "coveralls": "^2.11.2",
        "gulp": "^3.8.11",
        "gulp-pleeease": "^1.1.0",
        "gulp-sourcemaps": "^1.3.0",
        "mocha-lcov-reporter": "0.0.1",
        "mocha": "^2.1.0",
        "sinon": "^1.12.2",
        "vinyl-buffer": "^1.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
