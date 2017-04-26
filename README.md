# npmtest-express-fileupload

#### basic test coverage for  [express-fileupload (v0.1.2)](https://github.com/richardgirges/express-fileupload#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-fileupload.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-fileupload) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-fileupload.svg)](https://travis-ci.org/npmtest/node-npmtest-express-fileupload)

#### Simple express file upload middleware that wraps around Busboy

[![NPM](https://nodei.co/npm/express-fileupload.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-fileupload)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-fileupload/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-fileupload/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-fileupload/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-fileupload/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-fileupload/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-express-fileupload/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-express-fileupload/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-fileupload/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-fileupload/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-fileupload/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-fileupload/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-fileupload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-fileupload/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-fileupload/build/test-report.html](https://npmtest.github.io/node-npmtest-express-fileupload/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-fileupload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-fileupload/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-fileupload/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-fileupload/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-fileupload/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Girges"
    },
    "bugs": {
        "url": "https://github.com/richardgirges/express-fileupload/issues"
    },
    "dependencies": {
        "busboy": "^0.2.14",
        "fs-extra": "^0.22.1",
        "streamifier": "^0.1.1"
    },
    "description": "Simple express file upload middleware that wraps around Busboy",
    "devDependencies": {
        "body-parser": "^1.16.1",
        "coveralls": "^2.11.16",
        "eslint": "^3.15.0",
        "eslint-config-google": "^0.7.1",
        "express": "^4.13.4",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "supertest": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f7ba6f32568a3752e5bbffdcb8f4f047832fa98e",
        "tarball": "https://registry.npmjs.org/express-fileupload/-/express-fileupload-0.1.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "9c885440167a8d743307f93c7d901740dfad219f",
    "homepage": "https://github.com/richardgirges/express-fileupload#readme",
    "keywords": [
        "express",
        "file-upload",
        "upload",
        "forms",
        "multipart",
        "files",
        "busboy",
        "middleware"
    ],
    "license": "MIT",
    "main": "./lib/index",
    "maintainers": [
        {
            "name": "richardgirges"
        }
    ],
    "name": "express-fileupload",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/richardgirges/express-fileupload.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | coveralls",
        "lint": "eslint ./",
        "test": "istanbul cover _mocha -- -R spec"
    },
    "version": "0.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
