# npmtest-tern

#### basic test coverage for  [tern (v0.21.0)](https://github.com/ternjs/tern#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-tern.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-tern) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-tern.svg)](https://travis-ci.org/npmtest/node-npmtest-tern)

#### A JavaScript code analyzer for deep, cross-editor language support

[![NPM](https://nodei.co/npm/tern.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tern)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-tern/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-tern/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-tern/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-tern/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-tern/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-tern/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-tern/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-tern/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-tern/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-tern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-tern/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-tern/build/test-report.html](https://npmtest.github.io/node-npmtest-tern/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-tern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-tern/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-tern/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tern/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tern/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-tern/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-tern/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marijn Haverbeke"
    },
    "bin": {
        "tern": "./bin/tern"
    },
    "blint": {
        "allowedGlobals": [
            "tern",
            "acorn",
            "define",
            "clearTimeout",
            "setTimeout",
            "__dirname",
            "global",
            "process"
        ]
    },
    "bugs": {
        "url": "https://github.com/ternjs/tern/issues"
    },
    "contributors": [
        {
            "name": "List of Tern contributors. Updated before every release."
        },
        {
            "name": "A2ZH"
        },
        {
            "name": "Adam Faulkner"
        },
        {
            "name": "Adrian Toncean"
        },
        {
            "name": "Albertina Durante"
        },
        {
            "name": "Alex Pinder"
        },
        {
            "name": "Alex Saveliev"
        },
        {
            "name": "Amila Welihinda"
        },
        {
            "name": "Anders Thøgersen"
        },
        {
            "name": "angelozerr"
        },
        {
            "name": "Antonina Cherednichenko"
        },
        {
            "name": "Ben Joldersma"
        },
        {
            "name": "Ben McCormick"
        },
        {
            "name": "Boris Jonica"
        },
        {
            "name": "Brian Frichette"
        },
        {
            "name": "CentricStorm"
        },
        {
            "name": "chemzqm"
        },
        {
            "name": "Claus Reinke"
        },
        {
            "name": "Connor Osborn"
        },
        {
            "name": "Curtis Windatt"
        },
        {
            "name": "Damien Diederen"
        },
        {
            "name": "Dani Hodovic"
        },
        {
            "name": "Danny Su"
        },
        {
            "name": "Dewdrops"
        },
        {
            "name": "dloverin"
        },
        {
            "name": "Dmitry Gutov"
        },
        {
            "name": "Eloy Toro"
        },
        {
            "name": "Erik Tierney"
        },
        {
            "name": "Fabian Zeindl"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Francisc Romano"
        },
        {
            "name": "Francis Murillo"
        },
        {
            "name": "Hans Huebner"
        },
        {
            "name": "Hiroaki Otsu"
        },
        {
            "name": "Iku Iwasa"
        },
        {
            "name": "impinball"
        },
        {
            "name": "i-p"
        },
        {
            "name": "Jackson Ray Hamilton"
        },
        {
            "name": "J David Smith"
        },
        {
            "name": "Jeffrey Fisher"
        },
        {
            "name": "Jonathan Persson"
        },
        {
            "name": "Josh Giles"
        },
        {
            "name": "jzhang"
        },
        {
            "name": "katspaugh"
        },
        {
            "name": "Kim Se-won"
        },
        {
            "name": "Kyle P Davis"
        },
        {
            "name": "Marcel Gerber"
        },
        {
            "name": "Marcello Bastea-Forte"
        },
        {
            "name": "Marijn Haverbeke"
        },
        {
            "name": "Matt"
        },
        {
            "name": "Matthias Dahl"
        },
        {
            "name": "MetaMemoryT"
        },
        {
            "name": "Michael Russell"
        },
        {
            "name": "Michał Grzejszczak"
        },
        {
            "name": "Miguel Castillo"
        },
        {
            "name": "Mihai Bazon"
        },
        {
            "name": "Mike Rennie"
        },
        {
            "name": "Mikko Rantanen"
        },
        {
            "name": "Miroslav Bajtoš"
        },
        {
            "name": "Mounir Lamouri"
        },
        {
            "name": "Nate Eagleson"
        },
        {
            "name": "Nick Malaguti"
        },
        {
            "name": "Nicolas Petton"
        },
        {
            "name": "Nico Weber"
        },
        {
            "name": "Olivier Ligot"
        },
        {
            "name": "Ossi Herrala"
        },
        {
            "name": "othree"
        },
        {
            "name": "Paris Kasidiaris"
        },
        {
            "name": "Paul Bakker"
        },
        {
            "name": "Paul Verest"
        },
        {
            "name": "Peter Elmers"
        },
        {
            "name": "Peter Farland"
        },
        {
            "name": "Piotr Tomiak"
        },
        {
            "name": "Quinn Slack"
        },
        {
            "name": "Ralf Kistner"
        },
        {
            "name": "Randy Edmunds"
        },
        {
            "name": "Renato F"
        },
        {
            "name": "Renato Ferreira"
        },
        {
            "name": "Reuben Thomas"
        },
        {
            "name": "Ryan Stewart"
        },
        {
            "name": "SAKURAI Masashi"
        },
        {
            "name": "Sean Usick"
        },
        {
            "name": "Sergey Chikuyonok"
        },
        {
            "name": "Sérgio Ramos"
        },
        {
            "name": "sevin7676"
        },
        {
            "name": "Se-Won Kim"
        },
        {
            "name": "Sindre Sorhus"
        },
        {
            "name": "Slava Kim"
        },
        {
            "name": "Stephan Seidt"
        },
        {
            "name": "Steve Purcell"
        },
        {
            "name": "stoskov"
        },
        {
            "name": "Tim M. Madsen"
        },
        {
            "name": "Timothy Gu"
        },
        {
            "name": "Tommy Troy Lin"
        },
        {
            "name": "Trey Thomas"
        },
        {
            "name": "vheon"
        },
        {
            "name": "Vincent Woo"
        },
        {
            "name": "xd1le"
        }
    ],
    "dependencies": {
        "acorn": "^4.0.9",
        "enhanced-resolve": "^2.2.2",
        "glob": "^7.1.1",
        "minimatch": "^3.0.3",
        "resolve-from": "2.0.0"
    },
    "description": "A JavaScript code analyzer for deep, cross-editor language support",
    "devDependencies": {
        "codemirror": "git://github.com/codemirror/CodeMirror.git"
    },
    "directories": {},
    "dist": {
        "shasum": "809c87a826e112494398cf8894f7c2d1b3464eb7",
        "tarball": "https://registry.npmjs.org/tern/-/tern-0.21.0.tgz"
    },
    "gitHead": "e6a7777f273050098fa7074577ac196bae59d80b",
    "homepage": "https://github.com/ternjs/tern#readme",
    "license": "MIT",
    "main": "lib/tern.js",
    "maintainers": [
        {
            "name": "marijn"
        }
    ],
    "name": "tern",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ternjs/tern.git"
    },
    "scripts": {
        "test": "node ./bin/test"
    },
    "version": "0.21.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
