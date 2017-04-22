# npmdoc-bittorrent-tracker

#### api documentation for  [bittorrent-tracker (v9.2.2)](https://github.com/webtorrent/bittorrent-tracker#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-bittorrent-tracker.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bittorrent-tracker) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bittorrent-tracker.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bittorrent-tracker)

#### Simple, robust, BitTorrent tracker (client & server) implementation

[![NPM](https://nodei.co/npm/bittorrent-tracker.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bittorrent-tracker)

- [https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bittorrent-tracker/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "WebTorrent, LLC",
        "url": "https://webtorrent.io"
    },
    "bin": {
        "bittorrent-tracker": "./bin/cmd.js"
    },
    "browser": {
        "./lib/common-node.js": false,
        "./lib/client/http-tracker.js": false,
        "./lib/client/udp-tracker.js": false,
        "./server.js": false
    },
    "bugs": {
        "url": "https://github.com/webtorrent/bittorrent-tracker/issues"
    },
    "dependencies": {
        "bencode": "^0.11.0",
        "bittorrent-peerid": "^1.0.2",
        "bn.js": "^4.4.0",
        "bufferutil": "^3.0.0",
        "compact2string": "^1.2.0",
        "debug": "^2.0.0",
        "inherits": "^2.0.1",
        "ip": "^1.0.1",
        "lru": "^3.0.0",
        "minimist": "^1.1.1",
        "once": "^1.3.0",
        "random-iterate": "^1.0.1",
        "randombytes": "^2.0.3",
        "run-parallel": "^1.1.2",
        "run-series": "^1.0.2",
        "safe-buffer": "^5.0.0",
        "simple-get": "^2.0.0",
        "simple-peer": "^8.0.0",
        "simple-websocket": "^5.0.0",
        "string2compact": "^1.1.1",
        "uniq": "^1.0.1",
        "unordered-array-remove": "^1.0.2",
        "ws": "^2.2.0",
        "xtend": "^4.0.0"
    },
    "description": "Simple, robust, BitTorrent tracker (client & server) implementation",
    "devDependencies": {
        "electron-webrtc": "^0.3.0",
        "magnet-uri": "^5.1.3",
        "standard": "*",
        "tape": "^4.0.0",
        "webtorrent-fixtures": "^1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2031cf3465c0a6ac548f283d77d470e1378cce86",
        "tarball": "https://registry.npmjs.org/bittorrent-tracker/-/bittorrent-tracker-9.2.2.tgz"
    },
    "gitHead": "0b21ee6ddd35aa7c327720a1e439bbb0dbaa2dd1",
    "homepage": "https://github.com/webtorrent/bittorrent-tracker#readme",
    "keywords": [
        "bittorrent",
        "p2p",
        "peer",
        "peer-to-peer",
        "stream",
        "torrent",
        "tracker",
        "wire"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "feross"
        }
    ],
    "name": "bittorrent-tracker",
    "optionalDependencies": {
        "bufferutil": "^3.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/webtorrent/bittorrent-tracker.git"
    },
    "scripts": {
        "start": "node server.js",
        "test": "standard && tape test/*.js",
        "update-authors": "./bin/update-authors.sh"
    },
    "version": "9.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
