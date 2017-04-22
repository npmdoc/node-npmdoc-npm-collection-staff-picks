# npmdoc-npm-collection-staff-picks

#### api documentation for  [npm-collection-staff-picks (v1.0.2)](https://github.com/npm/npm-collection-staff-picks)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-collection-staff-picks.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-collection-staff-picks) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-collection-staff-picks.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-collection-staff-picks)

#### A list of obscure and beloved npm packages, selected by the staff at npm

[![NPM](https://nodei.co/npm/npm-collection-staff-picks.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-collection-staff-picks)

- [https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-collection-staff-picks/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-collection-staff-picks",
    "version": "1.0.2",
    "description": "A list of obscure and beloved npm packages, selected by the staff at npm",
    "main": "meta.json",
    "scripts": {
        "prepublish": "npm run meta",
        "meta": "node lib/meta.js",
        "postinstall": "backfill"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/npm/npm-collection-staff-picks"
    },
    "keywords": [
        "npm",
        "collection",
        "faves"
    ],
    "author": "zeke",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/npm/npm-collection-staff-picks/issues"
    },
    "homepage": "https://github.com/npm/npm-collection-staff-picks",
    "dependencies": {
        "backoff": "^2.4.0",
        "bistre": "^1.0.0",
        "blade": "^3.3.0",
        "bole": "^1.0.0",
        "cheerio": "^0.18.0",
        "dashdash": "^1.7.0",
        "inquirer": "^0.8.0",
        "json": "^9.0.2",
        "must": "^0.12.0",
        "nearley": "^1.0.1",
        "p-promise": "^0.4.8",
        "package-json-to-readme": "^1.0.1",
        "replify": "^1.2.0",
        "replpad": "^0.12.0",
        "shimmer": "^1.0.0",
        "sprintf-js": "^1.0.2",
        "stackup": "0.0.5",
        "standard-error": "^1.1.0",
        "superagent": "^0.20.0",
        "zeroclipboard": "^2.1.6"
    },
    "devDependencies": {
        "backfill": "^1.0.1",
        "find-root": "^0.1.1",
        "pkgs": "^1.2.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
