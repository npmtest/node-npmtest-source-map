# test coverage for  [source-map (v0.5.6)](https://github.com/mozilla/source-map)  [![npm package](https://img.shields.io/npm/v/npmtest-source-map.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-source-map) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-source-map.svg)](https://travis-ci.org/npmtest/node-npmtest-source-map)
#### Generates and consumes source maps

[![NPM](https://nodei.co/npm/source-map.png?downloads=true)](https://www.npmjs.com/package/source-map)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-source-map/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-source-map/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-source-map/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-source-map/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-source-map/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-source-map/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-source-map/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-source-map/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-source-map/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-source-map/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-source-map%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-source-map/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-source-map/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-source-map%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-source-map/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-source-map/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-source-map/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nick Fitzgerald",
        "email": "nfitzgerald@mozilla.com"
    },
    "bugs": {
        "url": "https://github.com/mozilla/source-map/issues"
    },
    "contributors": [
        {
            "name": "Tobias Koppers",
            "email": "tobias.koppers@googlemail.com"
        },
        {
            "name": "Duncan Beevers",
            "email": "duncan@dweebd.com"
        },
        {
            "name": "Stephen Crane",
            "email": "scrane@mozilla.com"
        },
        {
            "name": "Ryan Seddon",
            "email": "seddon.ryan@gmail.com"
        },
        {
            "name": "Miles Elam",
            "email": "miles.elam@deem.com"
        },
        {
            "name": "Mihai Bazon",
            "email": "mihai.bazon@gmail.com"
        },
        {
            "name": "Michael Ficarra",
            "email": "github.public.email@michael.ficarra.me"
        },
        {
            "name": "Todd Wolfson",
            "email": "todd@twolfson.com"
        },
        {
            "name": "Alexander Solovyov",
            "email": "alexander@solovyov.net"
        },
        {
            "name": "Felix Gnass",
            "email": "fgnass@gmail.com"
        },
        {
            "name": "Conrad Irwin",
            "email": "conrad.irwin@gmail.com"
        },
        {
            "name": "usrbincc",
            "email": "usrbincc@yahoo.com"
        },
        {
            "name": "David Glasser",
            "email": "glasser@davidglasser.net"
        },
        {
            "name": "Chase Douglas",
            "email": "chase@newrelic.com"
        },
        {
            "name": "Evan Wallace",
            "email": "evan.exe@gmail.com"
        },
        {
            "name": "Heather Arthur",
            "email": "fayearthur@gmail.com"
        },
        {
            "name": "Hugh Kennedy",
            "email": "hughskennedy@gmail.com"
        },
        {
            "name": "David Glasser",
            "email": "glasser@davidglasser.net"
        },
        {
            "name": "Simon Lydell",
            "email": "simon.lydell@gmail.com"
        },
        {
            "name": "Jmeas Smith",
            "email": "jellyes2@gmail.com"
        },
        {
            "name": "Michael Z Goddard",
            "email": "mzgoddard@gmail.com"
        },
        {
            "name": "azu",
            "email": "azu@users.noreply.github.com"
        },
        {
            "name": "John Gozde",
            "email": "john@gozde.ca"
        },
        {
            "name": "Adam Kirkton",
            "email": "akirkton@truefitinnovation.com"
        },
        {
            "name": "Chris Montgomery",
            "email": "christopher.montgomery@dowjones.com"
        },
        {
            "name": "J. Ryan Stinnett",
            "email": "jryans@gmail.com"
        },
        {
            "name": "Jack Herrington",
            "email": "jherrington@walmartlabs.com"
        },
        {
            "name": "Chris Truter",
            "email": "jeffpalentine@gmail.com"
        },
        {
            "name": "Daniel Espeset",
            "email": "daniel@danielespeset.com"
        },
        {
            "name": "Jamie Wong",
            "email": "jamie.lf.wong@gmail.com"
        },
        {
            "name": "Eddy Bruël",
            "email": "ejpbruel@mozilla.com"
        },
        {
            "name": "Hawken Rives",
            "email": "hawkrives@gmail.com"
        },
        {
            "name": "Gilad Peleg",
            "email": "giladp007@gmail.com"
        },
        {
            "name": "djchie",
            "email": "djchie.dev@gmail.com"
        },
        {
            "name": "Gary Ye",
            "email": "garysye@gmail.com"
        },
        {
            "name": "Nicolas Lalevée",
            "email": "nicolas.lalevee@hibnet.org"
        }
    ],
    "dependencies": {},
    "description": "Generates and consumes source maps",
    "devDependencies": {
        "doctoc": "^0.15.0",
        "webpack": "^1.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "75ce38f52bf0733c5a7f0c118d81334a2bb5f412",
        "tarball": "https://registry.npmjs.org/source-map/-/source-map-0.5.6.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "source-map.js",
        "lib/",
        "dist/source-map.debug.js",
        "dist/source-map.js",
        "dist/source-map.min.js",
        "dist/source-map.min.js.map"
    ],
    "gitHead": "aa0398ced67beebea34f0d36f766505656c344f6",
    "homepage": "https://github.com/mozilla/source-map",
    "license": "BSD-3-Clause",
    "main": "./source-map.js",
    "maintainers": [
        {
            "name": "mozilla-devtools",
            "email": "mozilla-developer-tools@googlegroups.com"
        },
        {
            "name": "mozilla",
            "email": "dherman@mozilla.com"
        },
        {
            "name": "nickfitzgerald",
            "email": "fitzgen@gmail.com"
        }
    ],
    "name": "source-map",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mozilla/source-map.git"
    },
    "scripts": {
        "build": "webpack --color",
        "test": "npm run build && node test/run-tests.js",
        "toc": "doctoc --title '## Table of Contents' README.md && doctoc --title '## Table of Contents' CONTRIBUTING.md"
    },
    "version": "0.5.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
