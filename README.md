# test coverage for  [bower-installer (v1.3.5)](https://github.com/rquadling/bower-installer#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bower-installer.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bower-installer) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bower-installer.svg)](https://travis-ci.org/npmtest/node-npmtest-bower-installer)
#### Tool for installing bower dependencies that won't include entire repos

[![NPM](https://nodei.co/npm/bower-installer.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bower-installer)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bower-installer/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-installer/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bower-installer/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bower-installer/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bower-installer/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bower-installer/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bower-installer/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bower-installer/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bower-installer/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bower-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bower-installer/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bower-installer/build/test-report.html](https://npmtest.github.io/node-npmtest-bower-installer/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bower-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bower-installer/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bower-installer/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bower-installer/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bower-installer/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bower-installer/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bower-installer/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bower-installer/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bret Little"
    },
    "bin": {
        "bower-installer": "./bower-installer.js"
    },
    "bugs": {
        "url": "https://github.com/rquadling/bower-installer/issues"
    },
    "contributors": [
        {
            "name": "Richard Quadling"
        }
    ],
    "dependencies": {
        "async": "^2.1.4",
        "bower": "^1.8.0",
        "colors": "^1.1.2",
        "glob": "^7.1.1",
        "lodash": "^4.17.2",
        "mkdirp": "^0.5.1",
        "node-fs": "~0.1.7",
        "nopt": "^3.0.6"
    },
    "description": "Tool for installing bower dependencies that won't include entire repos",
    "devDependencies": {
        "jasmine": "^2.5.2",
        "rimraf": "^2.5.4"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "2e43d126feb77621dc8822499c2b23bf6ee76f93",
        "tarball": "https://registry.npmjs.org/bower-installer/-/bower-installer-1.3.5.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "61708248944b44b461104f2afdf6665bd7cdd02a",
    "homepage": "https://github.com/rquadling/bower-installer#readme",
    "keywords": [
        "bower",
        "install",
        "dependencies"
    ],
    "license": "MIT",
    "main": "bower-installer.js",
    "maintainers": [
        {
            "name": "blittle"
        },
        {
            "name": "rquadling"
        }
    ],
    "name": "bower-installer",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rquadling/bower-installer.git"
    },
    "scripts": {
        "test": "jasmine JASMINE_CONFIG_PATH=test/jasmine.config.json"
    },
    "version": "1.3.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
