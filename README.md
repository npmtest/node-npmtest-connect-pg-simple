# npmtest-connect-pg-simple

#### basic test coverage for  [connect-pg-simple (v3.1.2)](https://github.com/voxpelli/node-connect-pg-simple#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-connect-pg-simple.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-connect-pg-simple) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-connect-pg-simple.svg)](https://travis-ci.org/npmtest/node-npmtest-connect-pg-simple)

#### A simple, minimal PostgreSQL session store for Connect/Express

[![NPM](https://nodei.co/npm/connect-pg-simple.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/connect-pg-simple)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-connect-pg-simple/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-connect-pg-simple/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-connect-pg-simple/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-connect-pg-simple/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-connect-pg-simple/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-connect-pg-simple/build/test-report.html](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-connect-pg-simple/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-connect-pg-simple/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-connect-pg-simple/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-connect-pg-simple/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-connect-pg-simple/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pelle Wessman",
        "url": "http://kodfabrik.se/"
    },
    "bugs": {
        "url": "https://github.com/voxpelli/node-connect-pg-simple/issues"
    },
    "dependencies": {
        "pg": ">=2.7.0-0 <5.0.0-0"
    },
    "description": "A simple, minimal PostgreSQL session store for Connect/Express",
    "devDependencies": {
        "chai": "^2.1.1",
        "coveralls": "^2.11.2",
        "grunt": "^0.4.5",
        "husky": "^0.10.2",
        "istanbul": "^0.3.7",
        "lintlovin": "github:voxpelli/lintlovin#1.x",
        "mocha": "^2.1.0",
        "promise": "^7.0.0",
        "sinon": "^1.13.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d11fb3755b5b535c1915be2b87fcd4fdd3e10950",
        "tarball": "https://registry.npmjs.org/connect-pg-simple/-/connect-pg-simple-3.1.2.tgz"
    },
    "engines": {
        "iojs": "*",
        "node": ">=0.10.0"
    },
    "gitHead": "6690c497a01c91dcbe954e246ce7f6dd78775012",
    "homepage": "https://github.com/voxpelli/node-connect-pg-simple#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "voxpelli"
        }
    ],
    "name": "connect-pg-simple",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/voxpelli/node-connect-pg-simple.git"
    },
    "scripts": {
        "prepush": "npm test",
        "test": "node -e \"require('grunt').tasks(['test']);\"",
        "test-all": "node -e \"require('grunt').tasks(['test-all']);\""
    },
    "url": "http://github.com/voxpelli/node-connect-pg-simple",
    "version": "3.1.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
