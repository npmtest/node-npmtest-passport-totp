# npmtest-passport-totp

#### basic test coverage for  [passport-totp (v0.0.2)](https://github.com/jaredhanson/passport-totp)  [![npm package](https://img.shields.io/npm/v/npmtest-passport-totp.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-passport-totp) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-passport-totp.svg)](https://travis-ci.org/npmtest/node-npmtest-passport-totp)

#### TOTP authentication strategy for Passport.

[![NPM](https://nodei.co/npm/passport-totp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/passport-totp)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-passport-totp/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-totp/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-passport-totp/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-passport-totp/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-passport-totp/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-passport-totp/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-passport-totp/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-passport-totp/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-passport-totp/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-passport-totp/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-passport-totp/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-passport-totp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-passport-totp/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-passport-totp/build/test-report.html](https://npmtest.github.io/node-npmtest-passport-totp/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-passport-totp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-passport-totp/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-passport-totp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-passport-totp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-passport-totp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-passport-totp/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-passport-totp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-passport-totp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/passport-totp/issues"
    },
    "dependencies": {
        "notp": "2.0.x",
        "passport-strategy": "1.0.0",
        "pkginfo": "0.2.x"
    },
    "description": "TOTP authentication strategy for Passport.",
    "devDependencies": {
        "chai": "1.x.x",
        "mocha": "1.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "3173815af6b75186f969fd4256be7ffd4c1be59a",
        "tarball": "https://registry.npmjs.org/passport-totp/-/passport-totp-0.0.2.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "fb124585fbe5f6a1a4e88351cd2f10e4b9ffa286",
    "homepage": "https://github.com/jaredhanson/passport-totp",
    "keywords": [
        "passport",
        "otp",
        "oath",
        "totp",
        "auth",
        "authn",
        "authentication"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "./lib",
    "maintainers": [
        {
            "name": "jaredhanson"
        }
    ],
    "name": "passport-totp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/passport-totp.git"
    },
    "scripts": {
        "test": "NODE_PATH=./lib node_modules/.bin/mocha --reporter spec --require test/bootstrap/node test/*.test.js"
    },
    "version": "0.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
