# npmtest-proxy

#### basic test coverage for  [proxy (v0.2.4)](https://github.com/TooTallNate/proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-proxy.svg)](https://travis-ci.org/npmtest/node-npmtest-proxy)

#### An HTTP proxy written with Node.js (think Squid)

[![NPM](https://nodei.co/npm/proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/proxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-proxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-proxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-proxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-proxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-proxy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-proxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-proxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-proxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-proxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-proxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-proxy/build/test-report.html](https://npmtest.github.io/node-npmtest-proxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-proxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-proxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nathan Rajlich",
        "url": "http://n8.io/"
    },
    "bin": {
        "proxy": "./bin/proxy"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/proxy/issues"
    },
    "dependencies": {
        "basic-auth-parser": "0.0.2",
        "commander": "2.9.0",
        "debug": "2.2.0"
    },
    "description": "An HTTP proxy written with Node.js (think Squid)",
    "devDependencies": {
        "mocha": "2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "bdd80e5efff3c33b2bf0bf2a10ce469bbb7d5e3e",
        "tarball": "https://registry.npmjs.org/proxy/-/proxy-0.2.4.tgz"
    },
    "gitHead": "7eef8b60df761261ab9da6b81aad094dbc8439c1",
    "homepage": "https://github.com/TooTallNate/proxy#readme",
    "keywords": [
        "http",
        "https",
        "proxy",
        "connect",
        "tunnel",
        "squid",
        "privoxy",
        "apache",
        "mod_proxy",
        "via",
        "x-forwarded-for"
    ],
    "license": "MIT",
    "main": "proxy.js",
    "maintainers": [
        {
            "name": "tootallnate"
        }
    ],
    "name": "proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/proxy.git"
    },
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "version": "0.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
