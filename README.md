# npmtest-pm2-windows-service

#### basic test coverage for  [pm2-windows-service (v0.2.0)](https://github.com/jon-hall/pm2-windows-service#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pm2-windows-service.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pm2-windows-service) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pm2-windows-service.svg)](https://travis-ci.org/npmtest/node-npmtest-pm2-windows-service)

#### Install PM2 as a service on windows

[![NPM](https://nodei.co/npm/pm2-windows-service.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pm2-windows-service)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pm2-windows-service/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pm2-windows-service/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pm2-windows-service/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pm2-windows-service/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pm2-windows-service/build/test-report.html](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pm2-windows-service/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pm2-windows-service/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pm2-windows-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pm2-windows-service/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pm2-windows-service/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pm2-windows-service",
    "version": "0.2.0",
    "description": "Install PM2 as a service on windows",
    "main": "src/index.js",
    "bin": {
        "pm2-service-install": "bin/pm2-service-install",
        "pm2-service-uninstall": "bin/pm2-service-uninstall"
    },
    "scripts": {
        "test": "node test/integration.js"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jon-hall/pm2-windows-service.git"
    },
    "keywords": [
        "pm2",
        "windows",
        "service"
    ],
    "author": "Jon Hall <jon_hall@outlook.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/jon-hall/pm2-windows-service/issues"
    },
    "homepage": "https://github.com/jon-hall/pm2-windows-service#readme",
    "dependencies": {
        "co": "^4.6.0",
        "co-event": "^0.1.0",
        "del": "^2.1.0",
        "fs-extra": "^0.26.2",
        "inquirer": "^1.1.2",
        "is-admin": "^1.0.2",
        "node-windows": "^0.1.10",
        "promisify-node": "^0.3.0",
        "shelljs": "^0.7.0",
        "yargs": "^4.7.1"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "os": [
        "win32"
    ],
    "devDependencies": {
        "temp": "^0.8.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
