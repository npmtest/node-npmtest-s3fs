# npmtest-s3fs

#### basic test coverage for  [s3fs (v2.5.0)](http://github.com/RiptideElements/s3fs)  [![npm package](https://img.shields.io/npm/v/npmtest-s3fs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-s3fs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-s3fs.svg)](https://travis-ci.org/npmtest/node-npmtest-s3fs)

#### Implementation of Node.JS FS interface using Amazon Simple Storage Service (S3).

[![NPM](https://nodei.co/npm/s3fs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/s3fs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-s3fs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3fs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-s3fs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-s3fs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-s3fs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-s3fs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-s3fs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-s3fs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-s3fs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-s3fs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-s3fs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-s3fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-s3fs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-s3fs/build/test-report.html](https://npmtest.github.io/node-npmtest-s3fs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-s3fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-s3fs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-s3fs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-s3fs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-s3fs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-s3fs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-s3fs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-s3fs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Pate",
        "url": "https://github.com/DavidTPate"
    },
    "bugs": {
        "url": "http://github.com/RiptideElements/s3fs/issues"
    },
    "contributors": [
        {
            "name": "Jhorlin De Armas",
            "url": "https://github.com/Jhorlin"
        }
    ],
    "dependencies": {
        "aws-sdk": "~2.5.2",
        "bluebird": "~3.4.1",
        "extend": "~3.x"
    },
    "description": "Implementation of Node.JS FS interface using Amazon Simple Storage Service (S3).",
    "devDependencies": {
        "buddy.js": "~0.x",
        "chai": "~3.x",
        "chai-as-promised": "~5.3.0",
        "dirty-chai": "~1.2.2",
        "eslint": "~3.3.1",
        "istanbul": "~0.4.5",
        "jscs": "~3.0.7",
        "jsinspect": "~0.x",
        "mocha": "~3.0.2",
        "nsp": "~2.6.1",
        "through2": "~2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9292e5fe31958be5394651540634c2768223487e",
        "tarball": "https://registry.npmjs.org/s3fs/-/s3fs-2.5.0.tgz"
    },
    "gitHead": "cede63b7176a72c0c740231213c4fd98d45e742d",
    "homepage": "http://github.com/RiptideElements/s3fs",
    "keywords": [
        "s3fs",
        "amazon s3",
        "aws s3",
        "fs",
        "file system",
        "simple storage service",
        "amazon"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "davidtpate"
        },
        {
            "name": "jhorlin"
        }
    ],
    "name": "s3fs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/RiptideElements/s3fs.git"
    },
    "scripts": {
        "cover": "istanbul cover _mocha -- --check-leaks --recursive --timeout=25000 test && istanbul check-coverage --statements 80.95 --branches 76.56 --functions 74.3 --lines 80.95",
        "lint": "eslint . && jscs . && jsinspect . && buddy --detect-objects index.js ./lib",
        "security": "nsp check",
        "test": "mocha --check-leaks --recursive --timeout=25000 test",
        "test-ci": "npm run lint && npm run security && npm run cover"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
