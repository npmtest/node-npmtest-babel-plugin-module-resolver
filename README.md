# npmtest-babel-plugin-module-resolver

#### basic test coverage for  [babel-plugin-module-resolver (v2.7.0)](https://github.com/tleunen/babel-plugin-module-resolver#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-babel-plugin-module-resolver.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-babel-plugin-module-resolver) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-babel-plugin-module-resolver.svg)](https://travis-ci.org/npmtest/node-npmtest-babel-plugin-module-resolver)

#### Module resolver plugin for Babel

[![NPM](https://nodei.co/npm/babel-plugin-module-resolver.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-module-resolver)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-babel-plugin-module-resolver/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-babel-plugin-module-resolver/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/test-report.html](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-module-resolver/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-module-resolver/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-module-resolver/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-module-resolver/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-babel-plugin-module-resolver/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tommy Leunen",
        "url": "http://tommyleunen.com"
    },
    "bugs": {
        "url": "https://github.com/tleunen/babel-plugin-module-resolver/issues"
    },
    "dependencies": {
        "find-babel-config": "^1.0.1",
        "glob": "^7.1.1",
        "resolve": "^1.2.0"
    },
    "description": "Module resolver plugin for Babel",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-jest": "^18.0.0",
        "babel-plugin-transform-object-rest-spread": "^6.22.0",
        "babel-preset-latest": "^6.22.0",
        "eslint": "^3.15.0",
        "eslint-config-airbnb-base": "^11.0.1",
        "eslint-plugin-import": "^2.2.0",
        "jest": "^18.1.0",
        "standard-version": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9c1cb2fcf2a1bdb45e91c6c985b96311123797f9",
        "tarball": "https://registry.npmjs.org/babel-plugin-module-resolver/-/babel-plugin-module-resolver-2.7.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "dc8849d6d25b451c1ed72ab9c231d15b057f6cf4",
    "greenkeeper": {
        "ignore": [
            "babel-jest",
            "eslint",
            "eslint-plugin-import"
        ]
    },
    "homepage": "https://github.com/tleunen/babel-plugin-module-resolver#readme",
    "jest": {
        "testRegex": "/test/.*\\.test\\.js$",
        "collectCoverageFrom": [
            "src/**/*.js"
        ]
    },
    "keywords": [
        "babel",
        "babel-plugin",
        "module",
        "resolver",
        "alias",
        "rewrite",
        "resolve",
        "rename",
        "mapping",
        "require",
        "import"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "tleunen"
        }
    ],
    "name": "babel-plugin-module-resolver",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tleunen/babel-plugin-module-resolver.git"
    },
    "scripts": {
        "compile": "babel src --out-dir lib",
        "lint": "eslint src test",
        "prepublish": "npm run compile",
        "pretest": "npm run lint",
        "release": "standard-version",
        "test": "jest --coverage",
        "test:suite": "jest",
        "test:watch": "jest --watch"
    },
    "version": "2.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
