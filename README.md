# npmtest-grunt-ftp-push

#### basic test coverage for  [grunt-ftp-push (v1.2.0)](http://robert-w.github.io/grunt-ftp-push)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-ftp-push.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-ftp-push) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-ftp-push.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-ftp-push)

#### Deploy your files to a FTP server.

[![NPM](https://nodei.co/npm/grunt-ftp-push.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-ftp-push)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-ftp-push/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-ftp-push/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-ftp-push/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-ftp-push/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-ftp-push/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-ftp-push/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-ftp-push/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-ftp-push/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-ftp-push/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Robert Winterbottom"
    },
    "bugs": {
        "url": "https://github.com/Robert-W/grunt-ftp-push/issues"
    },
    "dependencies": {
        "grunt": "^1.0.0",
        "jsftp": "^1.5.2"
    },
    "description": "Deploy your files to a FTP server.",
    "devDependencies": {
        "chai": "^3.2.0",
        "eslint": "^1.1.0",
        "ftp-test-server": "0.0.2",
        "mocha": "^2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ea1406472b0095821c26d9e4dd680f8c6e4e4b20",
        "tarball": "https://registry.npmjs.org/grunt-ftp-push/-/grunt-ftp-push-1.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "gitHead": "f09faa7e840f81d9e8d034e6873bf55f76a51172",
    "homepage": "http://robert-w.github.io/grunt-ftp-push",
    "keywords": [
        "gruntplugin",
        "grunt-ftp-push",
        "ftp",
        "jsftp",
        "mocha",
        "chai"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://robert-w.github.io/grunt-ftp-push/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "robert-w"
        }
    ],
    "name": "grunt-ftp-push",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Robert-W/grunt-ftp-push.git"
    },
    "scripts": {
        "ovh-test": "mocha ./test/jsftp/jsftpSpec.js",
        "test": "eslint tasks/*.js && eslint test/* && mocha ./test/*.js"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
