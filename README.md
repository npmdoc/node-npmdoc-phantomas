# api documentation for  [phantomas (v1.18.0)](https://github.com/macbre/phantomas#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-phantomas.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-phantomas) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-phantomas.svg)](https://travis-ci.org/npmdoc/node-npmdoc-phantomas)
#### PhantomJS-based web performance metrics collector

[![NPM](https://nodei.co/npm/phantomas.png?downloads=true)](https://www.npmjs.com/package/phantomas)

[![apidoc](https://npmdoc.github.io/node-npmdoc-phantomas/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-phantomas_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-phantomas/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-phantomas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-phantomas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "macbre",
        "email": "maciej.brencz@gmail.com",
        "url": "http://macbre.net"
    },
    "bin": {
        "phantomas": "./bin/phantomas.js"
    },
    "bugs": {
        "url": "https://github.com/macbre/phantomas/issues"
    },
    "contributors": [
        {
            "name": "macbre",
            "url": "https://github.com/macbre"
        },
        {
            "name": "gmetais",
            "url": "https://github.com/gmetais"
        },
        {
            "name": "sjhcockrell",
            "url": "https://github.com/sjhcockrell"
        },
        {
            "name": "jgonera",
            "url": "https://github.com/jgonera"
        },
        {
            "name": "william-p",
            "url": "https://github.com/william-p"
        },
        {
            "name": "vgangan",
            "url": "https://github.com/vgangan"
        },
        {
            "name": "cphoover",
            "url": "https://github.com/cphoover"
        },
        {
            "name": "iNem0o",
            "url": "https://github.com/iNem0o"
        },
        {
            "name": "wladekb",
            "url": "https://github.com/wladekb"
        },
        {
            "name": "EFF",
            "url": "https://github.com/EFF"
        },
        {
            "name": "gomezd",
            "url": "https://github.com/gomezd"
        },
        {
            "name": "stefanjudis",
            "url": "https://github.com/stefanjudis"
        },
        {
            "name": "kennydee",
            "url": "https://github.com/kennydee"
        },
        {
            "name": "rsnickell",
            "url": "https://github.com/rsnickell"
        },
        {
            "name": "vanng822",
            "url": "https://github.com/vanng822"
        },
        {
            "name": "ingoclaro",
            "url": "https://github.com/ingoclaro"
        },
        {
            "name": "sorensen",
            "url": "https://github.com/sorensen"
        },
        {
            "name": "rupl",
            "url": "https://github.com/rupl"
        },
        {
            "name": "cvan",
            "url": "https://github.com/cvan"
        },
        {
            "name": "alex-e-leon",
            "url": "https://github.com/alex-e-leon"
        },
        {
            "name": "dimichgh",
            "url": "https://github.com/dimichgh"
        },
        {
            "name": "camjc",
            "url": "https://github.com/camjc"
        },
        {
            "name": "hugoboos",
            "url": "https://github.com/hugoboos"
        },
        {
            "name": "LaurentGoderre",
            "url": "https://github.com/LaurentGoderre"
        },
        {
            "name": "nickcurry",
            "url": "https://github.com/nickcurry"
        },
        {
            "name": "r-kovalenko",
            "url": "https://github.com/r-kovalenko"
        },
        {
            "name": "vinvol",
            "url": "https://github.com/vinvol"
        }
    ],
    "dependencies": {
        "analyze-css": "^0.12.3",
        "ansicolors": "~0.3.2",
        "ansistyles": "~0.1.0",
        "ascii-table": "0.0.9",
        "async": "^2.0.1",
        "csv-string": "^2.3.0",
        "debug": "^2.2.0",
        "js-yaml": "^3.6.1",
        "node-statsd": "0.1.1",
        "node-uuid": "~1.4.1",
        "optimist": "0.6.x",
        "phantomjs-prebuilt": "^2.1.12",
        "progress": "~1.1.4",
        "q": "^1.4.1",
        "slimerjs": "^0.10.2",
        "tap-producer-macbre": "0.0.3",
        "travis-fold": ">=0.1.2"
    },
    "description": "PhantomJS-based web performance metrics collector",
    "devDependencies": {
        "glob": "^7.0.5",
        "http-server": "^0.9.0",
        "js-beautify": "^1.6.3",
        "jshint": "^2.9.2",
        "mockery": "^1.7.0",
        "vows": "^0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ebebc109b66e0be19375450c0b828dc8471e4ad5",
        "tarball": "https://registry.npmjs.org/phantomas/-/phantomas-1.18.0.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "gitHead": "de6a2cf4965b786f9bd3d4c33a6a8cb6519a1a7d",
    "homepage": "https://github.com/macbre/phantomas#readme",
    "jshintConfig": {
        "node": true,
        "-W020": false,
        "-W030": false
    },
    "keywords": [
        "high performance web sites",
        "metrics",
        "monitoring",
        "phantomas",
        "phantomjs",
        "web development",
        "webperf"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "macbre",
            "email": "maciej.brencz@gmail.com"
        }
    ],
    "name": "phantomas",
    "optionalDependencies": {
        "phantomjs-prebuilt": "^2.1.12",
        "slimerjs": "^0.10.2"
    },
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/macbre/phantomas.git"
    },
    "scripts": {
        "beautify": "js-beautify -r bin/phantomas.js core/*.js examples/*.js extensions/*/*.js lib/*.js lib/engines/*.js lib/metadata/*.js modules/*/*.js reporters/*.js scripts/*.js test/*.js test/*/*.js",
        "lint": "jshint --verbose core/ modules/ scripts/ test/*.js test/*/*-test.js lib/*.js lib/metadata/*.js reporters/ examples/",
        "metadata": "DEBUG=* node lib/metadata/generate.js",
        "test": "PHANTOMAS_ENGINE=webkit vows --spec",
        "unit-test": "vows test/modules/*-test.js --spec"
    },
    "version": "1.18.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module phantomas](#apidoc.module.phantomas)
1.  [function <span class="apidocSignatureSpan"></span>phantomas (params)](#apidoc.element.phantomas.phantomas)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>collection ()](#apidoc.element.phantomas.collection)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>engines (options)](#apidoc.element.phantomas.engines)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>ipc (stream)](#apidoc.element.phantomas.ipc)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>stats ()](#apidoc.element.phantomas.stats)
1.  object <span class="apidocSignatureSpan">phantomas.</span>ansicolors
1.  object <span class="apidocSignatureSpan">phantomas.</span>collection.prototype
1.  object <span class="apidocSignatureSpan">phantomas.</span>engines.prototype
1.  object <span class="apidocSignatureSpan">phantomas.</span>fast_stats
1.  object <span class="apidocSignatureSpan">phantomas.</span>ipc.prototype
1.  object <span class="apidocSignatureSpan">phantomas.</span>metadata
1.  object <span class="apidocSignatureSpan">phantomas.</span>optimist_config_file
1.  object <span class="apidocSignatureSpan">phantomas.</span>pads
1.  object <span class="apidocSignatureSpan">phantomas.</span>phantomas.prototype
1.  object <span class="apidocSignatureSpan">phantomas.</span>stats.prototype
1.  string <span class="apidocSignatureSpan">phantomas.</span>path
1.  string <span class="apidocSignatureSpan">phantomas.</span>version

#### [module phantomas.ansicolors](#apidoc.module.phantomas.ansicolors)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBlack (s)](#apidoc.element.phantomas.ansicolors.bgBlack)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBlue (s)](#apidoc.element.phantomas.ansicolors.bgBlue)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightBlack (s)](#apidoc.element.phantomas.ansicolors.bgBrightBlack)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightBlue (s)](#apidoc.element.phantomas.ansicolors.bgBrightBlue)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightCyan (s)](#apidoc.element.phantomas.ansicolors.bgBrightCyan)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightGreen (s)](#apidoc.element.phantomas.ansicolors.bgBrightGreen)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightMagenta (s)](#apidoc.element.phantomas.ansicolors.bgBrightMagenta)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightRed (s)](#apidoc.element.phantomas.ansicolors.bgBrightRed)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightWhite (s)](#apidoc.element.phantomas.ansicolors.bgBrightWhite)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightYellow (s)](#apidoc.element.phantomas.ansicolors.bgBrightYellow)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgCyan (s)](#apidoc.element.phantomas.ansicolors.bgCyan)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgGreen (s)](#apidoc.element.phantomas.ansicolors.bgGreen)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgMagenta (s)](#apidoc.element.phantomas.ansicolors.bgMagenta)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgRed (s)](#apidoc.element.phantomas.ansicolors.bgRed)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgWhite (s)](#apidoc.element.phantomas.ansicolors.bgWhite)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgYellow (s)](#apidoc.element.phantomas.ansicolors.bgYellow)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>black (s)](#apidoc.element.phantomas.ansicolors.black)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>blue (s)](#apidoc.element.phantomas.ansicolors.blue)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightBlack (s)](#apidoc.element.phantomas.ansicolors.brightBlack)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightBlue (s)](#apidoc.element.phantomas.ansicolors.brightBlue)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightCyan (s)](#apidoc.element.phantomas.ansicolors.brightCyan)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightGreen (s)](#apidoc.element.phantomas.ansicolors.brightGreen)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightMagenta (s)](#apidoc.element.phantomas.ansicolors.brightMagenta)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightRed (s)](#apidoc.element.phantomas.ansicolors.brightRed)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightWhite (s)](#apidoc.element.phantomas.ansicolors.brightWhite)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightYellow (s)](#apidoc.element.phantomas.ansicolors.brightYellow)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>cyan (s)](#apidoc.element.phantomas.ansicolors.cyan)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>disable ()](#apidoc.element.phantomas.ansicolors.disable)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>green (s)](#apidoc.element.phantomas.ansicolors.green)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>magenta (s)](#apidoc.element.phantomas.ansicolors.magenta)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>red (s)](#apidoc.element.phantomas.ansicolors.red)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>white (s)](#apidoc.element.phantomas.ansicolors.white)
1.  [function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>yellow (s)](#apidoc.element.phantomas.ansicolors.yellow)
1.  object <span class="apidocSignatureSpan">phantomas.ansicolors.</span>close
1.  object <span class="apidocSignatureSpan">phantomas.ansicolors.</span>open

#### [module phantomas.collection](#apidoc.module.phantomas.collection)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>collection ()](#apidoc.element.phantomas.collection.collection)

#### [module phantomas.collection.prototype](#apidoc.module.phantomas.collection.prototype)
1.  [function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>forEach (callback)](#apidoc.element.phantomas.collection.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>getLength ()](#apidoc.element.phantomas.collection.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>has (item)](#apidoc.element.phantomas.collection.prototype.has)
1.  [function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>push (item)](#apidoc.element.phantomas.collection.prototype.push)
1.  [function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>sort ()](#apidoc.element.phantomas.collection.prototype.sort)

#### [module phantomas.engines](#apidoc.module.phantomas.engines)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>engines (options)](#apidoc.element.phantomas.engines.engines)

#### [module phantomas.engines.prototype](#apidoc.module.phantomas.engines.prototype)
1.  [function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>getEngine (engine)](#apidoc.element.phantomas.engines.prototype.getEngine)
1.  [function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>getEngines ()](#apidoc.element.phantomas.engines.prototype.getEngines)
1.  [function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>registerEngine (engineName)](#apidoc.element.phantomas.engines.prototype.registerEngine)
1.  [function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>run (scriptFile)](#apidoc.element.phantomas.engines.prototype.run)

#### [module phantomas.fast_stats](#apidoc.module.phantomas.fast_stats)
1.  [function <span class="apidocSignatureSpan">phantomas.fast_stats.</span>Stats (c)](#apidoc.element.phantomas.fast_stats.Stats)

#### [module phantomas.ipc](#apidoc.module.phantomas.ipc)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>ipc (stream)](#apidoc.element.phantomas.ipc.ipc)

#### [module phantomas.ipc.prototype](#apidoc.module.phantomas.ipc.prototype)
1.  [function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>init ()](#apidoc.element.phantomas.ipc.prototype.init)
1.  [function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>on (event, fn)](#apidoc.element.phantomas.ipc.prototype.on)
1.  [function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>parse (data)](#apidoc.element.phantomas.ipc.prototype.parse)
1.  [function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>setEventEmitter (emitter)](#apidoc.element.phantomas.ipc.prototype.setEventEmitter)

#### [module phantomas.optimist_config_file](#apidoc.module.phantomas.optimist_config_file)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>alias (x, y)](#apidoc.element.phantomas.optimist_config_file.alias)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>boolean (bools)](#apidoc.element.phantomas.optimist_config_file.boolean)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>check (f)](#apidoc.element.phantomas.optimist_config_file.check)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>default (key, value)](#apidoc.element.phantomas.optimist_config_file.default)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>demand (keys)](#apidoc.element.phantomas.optimist_config_file.demand)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>describe (opt)](#apidoc.element.phantomas.optimist_config_file.describe)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>header (s)](#apidoc.element.phantomas.optimist_config_file.header)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>help ()](#apidoc.element.phantomas.optimist_config_file.help)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>option (key, opt)](#apidoc.element.phantomas.optimist_config_file.option)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>options (key, opt)](#apidoc.element.phantomas.optimist_config_file.options)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>parse (args)](#apidoc.element.phantomas.optimist_config_file.parse)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>setConfigFile (configFileParam)](#apidoc.element.phantomas.optimist_config_file.setConfigFile)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>showHelp (fn)](#apidoc.element.phantomas.optimist_config_file.showHelp)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>string (strings)](#apidoc.element.phantomas.optimist_config_file.string)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>usage (msg, opts)](#apidoc.element.phantomas.optimist_config_file.usage)
1.  [function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>wrap (cols)](#apidoc.element.phantomas.optimist_config_file.wrap)
1.  object <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>argv

#### [module phantomas.pads](#apidoc.module.phantomas.pads)
1.  [function <span class="apidocSignatureSpan">phantomas.pads.</span>lpad (str, len)](#apidoc.element.phantomas.pads.lpad)
1.  [function <span class="apidocSignatureSpan">phantomas.pads.</span>rpad (str, len)](#apidoc.element.phantomas.pads.rpad)

#### [module phantomas.phantomas](#apidoc.module.phantomas.phantomas)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>phantomas (params)](#apidoc.element.phantomas.phantomas.phantomas)
1.  string <span class="apidocSignatureSpan">phantomas.phantomas.</span>version

#### [module phantomas.phantomas.prototype](#apidoc.module.phantomas.phantomas.prototype)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addCoreModule (name)](#apidoc.element.phantomas.phantomas.prototype.addCoreModule)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addExtension (name)](#apidoc.element.phantomas.phantomas.prototype.addExtension)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addModule (name)](#apidoc.element.phantomas.phantomas.prototype.addModule)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addModuleInDir (dir, name)](#apidoc.element.phantomas.phantomas.prototype.addModuleInDir)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addOffender ()](#apidoc.element.phantomas.phantomas.prototype.addOffender)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addToAvgMetric (name, value)](#apidoc.element.phantomas.phantomas.prototype.addToAvgMetric)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>echo (msg)](#apidoc.element.phantomas.phantomas.prototype.echo)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>emit ()](#apidoc.element.phantomas.phantomas.prototype.emit)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>emitInternal ()](#apidoc.element.phantomas.phantomas.prototype.emitInternal)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getMetric (name)](#apidoc.element.phantomas.phantomas.prototype.getMetric)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getParam (key, defValue, typeCheck)](#apidoc.element.phantomas.phantomas.prototype.getParam)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getPublicWrapper ()](#apidoc.element.phantomas.phantomas.prototype.getPublicWrapper)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getSource ()](#apidoc.element.phantomas.phantomas.prototype.getSource)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getVersion ()](#apidoc.element.phantomas.phantomas.prototype.getVersion)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>incrMetric (name, incr)](#apidoc.element.phantomas.phantomas.prototype.incrMetric)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>initLoadingProgress ()](#apidoc.element.phantomas.phantomas.prototype.initLoadingProgress)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listExtensions ()](#apidoc.element.phantomas.phantomas.prototype.listExtensions)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listModules ()](#apidoc.element.phantomas.phantomas.prototype.listModules)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listModulesInDir (modulesDir)](#apidoc.element.phantomas.phantomas.prototype.listModulesInDir)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>log ()](#apidoc.element.phantomas.phantomas.prototype.log)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>on (ev, fn)](#apidoc.element.phantomas.phantomas.prototype.on)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onAlert (msg)](#apidoc.element.phantomas.phantomas.prototype.onAlert)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onCallback (msg)](#apidoc.element.phantomas.phantomas.prototype.onCallback)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onConfirm (msg)](#apidoc.element.phantomas.phantomas.prototype.onConfirm)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onConsoleMessage (msg)](#apidoc.element.phantomas.phantomas.prototype.onConsoleMessage)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onError (msg, trace)](#apidoc.element.phantomas.phantomas.prototype.onError)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onInitialized ()](#apidoc.element.phantomas.phantomas.prototype.onInitialized)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onLoadFinished (status)](#apidoc.element.phantomas.phantomas.prototype.onLoadFinished)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onLoadStarted (url, isFrame)](#apidoc.element.phantomas.phantomas.prototype.onLoadStarted)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onPrompt (msg)](#apidoc.element.phantomas.phantomas.prototype.onPrompt)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onResourceReceived (res)](#apidoc.element.phantomas.phantomas.prototype.onResourceReceived)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onResourceRequested (res, request)](#apidoc.element.phantomas.phantomas.prototype.onResourceRequested)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>once (ev, fn)](#apidoc.element.phantomas.phantomas.prototype.once)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>proxy (fn, scope)](#apidoc.element.phantomas.phantomas.prototype.proxy)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>report ()](#apidoc.element.phantomas.phantomas.prototype.report)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>require (module)](#apidoc.element.phantomas.phantomas.prototype.require)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>run ()](#apidoc.element.phantomas.phantomas.prototype.run)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>runScript (script, args, callback)](#apidoc.element.phantomas.phantomas.prototype.runScript)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMarkerMetric (name)](#apidoc.element.phantomas.phantomas.prototype.setMarkerMetric)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMetric (name, value, isFinal)](#apidoc.element.phantomas.phantomas.prototype.setMetric)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMetricEvaluate (name, fn)](#apidoc.element.phantomas.phantomas.prototype.setMetricEvaluate)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>tearDown (exitCode, msg)](#apidoc.element.phantomas.phantomas.prototype.tearDown)
1.  [function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>tmpdir ()](#apidoc.element.phantomas.phantomas.prototype.tmpdir)

#### [module phantomas.stats](#apidoc.module.phantomas.stats)
1.  [function <span class="apidocSignatureSpan">phantomas.</span>stats ()](#apidoc.element.phantomas.stats.stats)

#### [module phantomas.stats.prototype](#apidoc.module.phantomas.stats.prototype)
1.  [function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getAvailableStats ()](#apidoc.element.phantomas.stats.prototype.getAvailableStats)
1.  [function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getMetricStats (metricName)](#apidoc.element.phantomas.stats.prototype.getMetricStats)
1.  [function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getMetrics ()](#apidoc.element.phantomas.stats.prototype.getMetrics)
1.  [function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>pushMetrics (metrics)](#apidoc.element.phantomas.stats.prototype.pushMetrics)



# <a name="apidoc.module.phantomas"></a>[module phantomas](#apidoc.module.phantomas)

#### <a name="apidoc.element.phantomas.phantomas"></a>[function <span class="apidocSignatureSpan"></span>phantomas (params)](#apidoc.element.phantomas.phantomas)
- description and source-code
```javascript
phantomas = function (params) {
	var fs = require('fs');

	// store script CLI parameters
	this.params = params;

	// --url=http://example.com
	this.url = params.url;

	// --format
	this.format = params.format;

	// --verbose
	this.verboseMode = params.verbose === true;

	// --silent
	this.silentMode = params.silent === true;

	// --timeout (in seconds)
	this.timeout = (params.timeout > 0 && parseInt(params.timeout, 10)) || 15;

	// --modules=localStorage,cookies
	this.modules = (typeof params.modules === 'string') ? params.modules.split(',') : [];

	// --include-dirs=dirOne,dirTwo
	this.includeDirs = (typeof params['include-dirs'] === 'string') ? params['include-dirs'].split(',') : [];

	// --skip-modules=jQuery,domQueries
	this.skipModules = (typeof params['skip-modules'] === 'string') ? params['skip-modules'].split(',') : [];

	// disable JavaScript on the page that will be loaded
	this.disableJs = params['disable-js'] === true;

	// setup the stuff
	this.emitter = new(this.require('events').EventEmitter)();
	this.emitter.setMaxListeners(200);
	this.ipc = require('./ipc');

	this.util = this.require('util');

	this.page = require('webpage').create();

	// store the timestamp of responseEnd event
	// should be bound before modules
	this.on('responseEnd', this.proxy(function() {
		this.responseEndTime = Date.now();
	}));

	// setup logger
	var Logger = require('./logger'),
		logFile = params.log || '';

	this.logger = new Logger(logFile, {
		beVerbose: this.verboseMode,
		beSilent: this.silentMode
	});

	// detect phantomas working directory
	if (typeof module.dirname !== 'undefined') {
		this.dir = module.dirname.replace(/core$/, '');
	} else if (typeof slimer !== 'undefined') {
		var args = require('system').args;
		this.dir = fs.dirname(args[0]).replace(/scripts$/, '');
	}

	this.log('phantomas v%s: %s', this.getVersion(), this.dir);
	this.log('Options: %j', this.params);

	// queue of jobs that needs to be done before report can be generated
	var Queue = require('../lib/simple-queue');
	this.reportQueue = new Queue();

	// set up results wrapper
	var Results = require('./results');
	this.results = new Results();

	this.results.setGenerator('phantomas v' + this.getVersion());
	this.results.setUrl(this.url);

	this.metricsAvgStorage = {};

	// allow asserts to be provided via command-line options (#128)
	Object.keys(this.params).forEach(function(param) {
		var value = parseFloat(this.params[param]),
			name;

		if (!isNaN(value) && param.indexOf('assert-') === 0) {
			name = param.substr(7);

			if (name.length > 0) {
				this.results.setAssert(name, value);
			}
		}
	}, this);

	// load core modules
	this.log('Loading: core modules...');
	this.addCoreModule('navigationTiming');
	this.addCoreModule('requestsMonitor');
	this.addCoreModule('timeToFirstByte');

	// load extensions
	this.log('Loading: extensions...');
	var extensions = this.listExtensions();
	extensions.forEach(this.addExtension, this);

	// load modules
	this.log('Loading: modules...');
	var modules = (this.modules.length > 0) ? this.modules : this.listModules();
	modules.forEach(this.addModule, this);

	// load 3rd party modules
	this.log('Loading: 3rd party modules...');
	this.includeDirs.forEach(function(dirName) {
		var dirPath = fs.absolute(dirName),
			dirModules = this.listModulesInDir(dirPath);

		dirModules.forEach(function(moduleName) {
			this.addModuleInDir(dirPath, moduleName);
		}, this);

	}, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.collection"></a>[function <span class="apidocSignatureSpan">phantomas.</span>collection ()](#apidoc.element.phantomas.collection)
- description and source-code
```javascript
function collection() {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.items = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.engines"></a>[function <span class="apidocSignatureSpan">phantomas.</span>engines (options)](#apidoc.element.phantomas.engines)
- description and source-code
```javascript
function engines(options) {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.options = options;

	//--debug can be either 'true' or 'false'
	this.options.debug = (this.options.debug === true) ? 'true' : 'false';

	// engines storage
	this.engines = {};
	[
		// the first one is a default one
		'webkit',
		'gecko'
	].forEach(this.registerEngine, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ipc"></a>[function <span class="apidocSignatureSpan">phantomas.</span>ipc (stream)](#apidoc.element.phantomas.ipc)
- description and source-code
```javascript
function ipc(stream) {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.stream = stream;
	this.events = new emitter();

	this.init();
}
```
- example usage
```shell
...
	// emit given event and pass it to CommonJS API via IPC
	emit: function( /* eventName, arg1, arg2, ... */ ) {
		this.emitInternal.apply(this, arguments);

		// pass it via IPC
		var args = Array.prototype.slice.apply(arguments),
			eventName = args.shift(),
			ipc = new this.ipc(eventName);

		ipc.push.apply(ipc, args);
	},

	// emit given event "internally"
	emitInternal: function( /* eventName, arg1, arg2, ... */ ) {
		this.log('Event %s emitted', arguments[0]);
...
```

#### <a name="apidoc.element.phantomas.stats"></a>[function <span class="apidocSignatureSpan">phantomas.</span>stats ()](#apidoc.element.phantomas.stats)
- description and source-code
```javascript
function stats() {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	// use pushMetrics() to add results for each run
	this.metrics = [];
	this.runs = 0;

	// stats to be calculated
	// @see https://github.com/bluesmoon/node-faststats
	this.stats = {
		min: function(values) {
			return values.range()[0];
		},
		max: function(values) {
			return values.range()[1];
		},
		average: function(values) {
			return values.amean().toFixed(2);
		},
		median: function(values) {
			return values.median().toFixed(2);
		},
		stddev: function(values) {
			return values.stddev().toFixed(2);
		}
	};

	this.statsNames = Object.keys(this.stats);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.ansicolors"></a>[module phantomas.ansicolors](#apidoc.module.phantomas.ansicolors)

#### <a name="apidoc.element.phantomas.ansicolors.bgBlack"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBlack (s)](#apidoc.element.phantomas.ansicolors.bgBlack)
- description and source-code
```javascript
bgBlack = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBlue"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBlue (s)](#apidoc.element.phantomas.ansicolors.bgBlue)
- description and source-code
```javascript
bgBlue = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightBlack"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightBlack (s)](#apidoc.element.phantomas.ansicolors.bgBrightBlack)
- description and source-code
```javascript
bgBrightBlack = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightBlue"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightBlue (s)](#apidoc.element.phantomas.ansicolors.bgBrightBlue)
- description and source-code
```javascript
bgBrightBlue = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightCyan"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightCyan (s)](#apidoc.element.phantomas.ansicolors.bgBrightCyan)
- description and source-code
```javascript
bgBrightCyan = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightGreen"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightGreen (s)](#apidoc.element.phantomas.ansicolors.bgBrightGreen)
- description and source-code
```javascript
bgBrightGreen = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightMagenta"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightMagenta (s)](#apidoc.element.phantomas.ansicolors.bgBrightMagenta)
- description and source-code
```javascript
bgBrightMagenta = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightRed"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightRed (s)](#apidoc.element.phantomas.ansicolors.bgBrightRed)
- description and source-code
```javascript
bgBrightRed = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightWhite"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightWhite (s)](#apidoc.element.phantomas.ansicolors.bgBrightWhite)
- description and source-code
```javascript
bgBrightWhite = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgBrightYellow"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgBrightYellow (s)](#apidoc.element.phantomas.ansicolors.bgBrightYellow)
- description and source-code
```javascript
bgBrightYellow = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgCyan"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgCyan (s)](#apidoc.element.phantomas.ansicolors.bgCyan)
- description and source-code
```javascript
bgCyan = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgGreen"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgGreen (s)](#apidoc.element.phantomas.ansicolors.bgGreen)
- description and source-code
```javascript
bgGreen = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgMagenta"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgMagenta (s)](#apidoc.element.phantomas.ansicolors.bgMagenta)
- description and source-code
```javascript
bgMagenta = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgRed"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgRed (s)](#apidoc.element.phantomas.ansicolors.bgRed)
- description and source-code
```javascript
bgRed = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgWhite"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgWhite (s)](#apidoc.element.phantomas.ansicolors.bgWhite)
- description and source-code
```javascript
bgWhite = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.bgYellow"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>bgYellow (s)](#apidoc.element.phantomas.ansicolors.bgYellow)
- description and source-code
```javascript
bgYellow = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.black"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>black (s)](#apidoc.element.phantomas.ansicolors.black)
- description and source-code
```javascript
black = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.blue"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>blue (s)](#apidoc.element.phantomas.ansicolors.blue)
- description and source-code
```javascript
blue = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.brightBlack"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightBlack (s)](#apidoc.element.phantomas.ansicolors.brightBlack)
- description and source-code
```javascript
brightBlack = function (s) {
  return o + s + c;
}
```
- example usage
```shell
...
			// error!
			if (/!$/.test(consoleMsg) || /Error:/.test(consoleMsg)) {
				consoleMsg = colors.brightRed(styles.bright(consoleMsg));
			}
			// label: message
			else if (/^(.*): /.test(consoleMsg)) {
				var idx = consoleMsg.indexOf(': ') + 1;
				consoleMsg = colors.brightGreen(consoleMsg.substr(0, idx)) + colors.brightBlack(consoleMsg.substr(idx));
			}
			// the rest
			else {
				consoleMsg = colors.brightBlack(consoleMsg);
			}

			if (!beSilent) {
...
```

#### <a name="apidoc.element.phantomas.ansicolors.brightBlue"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightBlue (s)](#apidoc.element.phantomas.ansicolors.brightBlue)
- description and source-code
```javascript
brightBlue = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.brightCyan"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightCyan (s)](#apidoc.element.phantomas.ansicolors.brightCyan)
- description and source-code
```javascript
brightCyan = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.brightGreen"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightGreen (s)](#apidoc.element.phantomas.ansicolors.brightGreen)
- description and source-code
```javascript
brightGreen = function (s) {
  return o + s + c;
}
```
- example usage
```shell
...
			// error!
			if (/!$/.test(consoleMsg) || /Error:/.test(consoleMsg)) {
				consoleMsg = colors.brightRed(styles.bright(consoleMsg));
			}
			// label: message
			else if (/^(.*): /.test(consoleMsg)) {
				var idx = consoleMsg.indexOf(': ') + 1;
				consoleMsg = colors.brightGreen(consoleMsg.substr(0, idx)) + colors.brightBlack(consoleMsg.substr(idx));
			}
			// the rest
			else {
				consoleMsg = colors.brightBlack(consoleMsg);
			}

			if (!beSilent) {
...
```

#### <a name="apidoc.element.phantomas.ansicolors.brightMagenta"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightMagenta (s)](#apidoc.element.phantomas.ansicolors.brightMagenta)
- description and source-code
```javascript
brightMagenta = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.brightRed"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightRed (s)](#apidoc.element.phantomas.ansicolors.brightRed)
- description and source-code
```javascript
brightRed = function (s) {
  return o + s + c;
}
```
- example usage
```shell
...

		// log to the console (--verbose)
		if (beVerbose) {
			var consoleMsg = msg;

			// error!
			if (/!$/.test(consoleMsg) || /Error:/.test(consoleMsg)) {
				consoleMsg = colors.brightRed(styles.bright(consoleMsg));
			}
			// label: message
			else if (/^(.*): /.test(consoleMsg)) {
				var idx = consoleMsg.indexOf(': ') + 1;
				consoleMsg = colors.brightGreen(consoleMsg.substr(0, idx)) + colors.brightBlack(consoleMsg.substr(idx));
			}
			// the rest
...
```

#### <a name="apidoc.element.phantomas.ansicolors.brightWhite"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightWhite (s)](#apidoc.element.phantomas.ansicolors.brightWhite)
- description and source-code
```javascript
brightWhite = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.brightYellow"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>brightYellow (s)](#apidoc.element.phantomas.ansicolors.brightYellow)
- description and source-code
```javascript
brightYellow = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.cyan"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>cyan (s)](#apidoc.element.phantomas.ansicolors.cyan)
- description and source-code
```javascript
cyan = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.disable"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>disable ()](#apidoc.element.phantomas.ansicolors.disable)
- description and source-code
```javascript
function disable() {
	keys.forEach(function(key) {
		colors[key] = nop;
	});
}
```
- example usage
```shell
...
	var isMultiple = Array.isArray(results),
		noColor = (reporterOptions['no-color'] === true);

	function formatSingleRunResults(results) {
		var res = [];

		if (noColor) {
			colors.disable();
		}

		// header
		res.push(results.getGenerator() + ' metrics for <' + results.getUrl() + '>:');
		res.push('');

		// metrics
...
```

#### <a name="apidoc.element.phantomas.ansicolors.green"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>green (s)](#apidoc.element.phantomas.ansicolors.green)
- description and source-code
```javascript
green = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.magenta"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>magenta (s)](#apidoc.element.phantomas.ansicolors.magenta)
- description and source-code
```javascript
magenta = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.red"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>red (s)](#apidoc.element.phantomas.ansicolors.red)
- description and source-code
```javascript
red = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.white"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>white (s)](#apidoc.element.phantomas.ansicolors.white)
- description and source-code
```javascript
white = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.ansicolors.yellow"></a>[function <span class="apidocSignatureSpan">phantomas.ansicolors.</span>yellow (s)](#apidoc.element.phantomas.ansicolors.yellow)
- description and source-code
```javascript
yellow = function (s) {
  return o + s + c;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.collection"></a>[module phantomas.collection](#apidoc.module.phantomas.collection)

#### <a name="apidoc.element.phantomas.collection.collection"></a>[function <span class="apidocSignatureSpan">phantomas.</span>collection ()](#apidoc.element.phantomas.collection.collection)
- description and source-code
```javascript
function collection() {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.items = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.collection.prototype"></a>[module phantomas.collection.prototype](#apidoc.module.phantomas.collection.prototype)

#### <a name="apidoc.element.phantomas.collection.prototype.forEach"></a>[function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>forEach (callback)](#apidoc.element.phantomas.collection.prototype.forEach)
- description and source-code
```javascript
forEach = function (callback) {
		Object.keys(this.items).forEach(function(key) {
			callback(key, this.items[key].cnt);
		}, this);
	}
```
- example usage
```shell
...

	this.results.setGenerator('phantomas v' + this.getVersion());
	this.results.setUrl(this.url);

	this.metricsAvgStorage = {};

	// allow asserts to be provided via command-line options (#128)
	Object.keys(this.params).forEach(function(param) {
		var value = parseFloat(this.params[param]),
			name;

		if (!isNaN(value) && param.indexOf('assert-') === 0) {
			name = param.substr(7);

			if (name.length > 0) {
...
```

#### <a name="apidoc.element.phantomas.collection.prototype.getLength"></a>[function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>getLength ()](#apidoc.element.phantomas.collection.prototype.getLength)
- description and source-code
```javascript
getLength = function () {
		return Object.keys(this.items).length;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.collection.prototype.has"></a>[function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>has (item)](#apidoc.element.phantomas.collection.prototype.has)
- description and source-code
```javascript
has = function (item) {
		return (typeof this.items[item] !== 'undefined');
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.collection.prototype.push"></a>[function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>push (item)](#apidoc.element.phantomas.collection.prototype.push)
- description and source-code
```javascript
push = function (item) {
		if (typeof this.items[item] === 'undefined') {
			this.items[item] = {
				cnt: 1
			};
		} else {
			this.items[item].cnt++;
		}
	}
```
- example usage
```shell
...
			}
			// the rest
			else {
				consoleMsg = colors.brightBlack(consoleMsg);
			}

			if (!beSilent) {
				ipc.push(ts + ' ' + consoleMsg);
			}
		}

		// log to the file (--log)
		if (stream) {
			stream.writeLine(ts + ': ' + msg);
			stream.flush();
...
```

#### <a name="apidoc.element.phantomas.collection.prototype.sort"></a>[function <span class="apidocSignatureSpan">phantomas.collection.prototype.</span>sort ()](#apidoc.element.phantomas.collection.prototype.sort)
- description and source-code
```javascript
sort = function () {
		var newItems = {},
			sortedKeys;

		// sort in descending order (by cnt)
		sortedKeys = Object.keys(this.items).sort((function(a, b) {
			return this.items[b].cnt - this.items[a].cnt;
		}).bind(this));

		// build new items dictionary
		sortedKeys.forEach(function(key) {
			newItems[key] = this.items[key];
		}, this);

		this.items = newItems;
		return this;
	}
```
- example usage
```shell
...
			if (fs.isDirectory(modulesDir + '/' + entry) && fs.isFile(modulesDir + '/' + entry + '/' + entry + '.js')) {
				modules.push(entry);
			}
		});

		// SlimerJS 'fs.list' does not order the returned array
		// PhantomJS does that, so be consistent here :)
		return modules.sort();
	},

	// setup polling for loading progress (issue #204)
	// pipe JSON messages over stderr
	initLoadingProgress: function() {
		var currentProgress = false;
...
```



# <a name="apidoc.module.phantomas.engines"></a>[module phantomas.engines](#apidoc.module.phantomas.engines)

#### <a name="apidoc.element.phantomas.engines.engines"></a>[function <span class="apidocSignatureSpan">phantomas.</span>engines (options)](#apidoc.element.phantomas.engines.engines)
- description and source-code
```javascript
function engines(options) {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.options = options;

	//--debug can be either 'true' or 'false'
	this.options.debug = (this.options.debug === true) ? 'true' : 'false';

	// engines storage
	this.engines = {};
	[
		// the first one is a default one
		'webkit',
		'gecko'
	].forEach(this.registerEngine, this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.engines.prototype"></a>[module phantomas.engines.prototype](#apidoc.module.phantomas.engines.prototype)

#### <a name="apidoc.element.phantomas.engines.prototype.getEngine"></a>[function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>getEngine (engine)](#apidoc.element.phantomas.engines.prototype.getEngine)
- description and source-code
```javascript
getEngine = function (engine) {
	return this.engines[engine];
}
```
- example usage
```shell
...
engines.prototype.getEngine = function(engine) {
	return this.engines[engine];
};

engines.prototype.run = function(scriptFile) {
	// select the engine
	var engines = this.getEngines(),
		engine = this.getEngine(engines[0]);

	// --engine=[gecko|webkit]
	if (typeof this.options.engine === 'string') {
		engine = this.getEngine(this.options.engine);

		if (typeof engine === 'undefined') {
			throw 'Engine "' + this.options.engine + '" not found!';
...
```

#### <a name="apidoc.element.phantomas.engines.prototype.getEngines"></a>[function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>getEngines ()](#apidoc.element.phantomas.engines.prototype.getEngines)
- description and source-code
```javascript
getEngines = function () {
	return Object.keys(this.engines);
}
```
- example usage
```shell
...

engines.prototype.getEngine = function(engine) {
	return this.engines[engine];
};

engines.prototype.run = function(scriptFile) {
	// select the engine
	var engines = this.getEngines(),
		engine = this.getEngine(engines[0]);

	// --engine=[gecko|webkit]
	if (typeof this.options.engine === 'string') {
		engine = this.getEngine(this.options.engine);

		if (typeof engine === 'undefined') {
...
```

#### <a name="apidoc.element.phantomas.engines.prototype.registerEngine"></a>[function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>registerEngine (engineName)](#apidoc.element.phantomas.engines.prototype.registerEngine)
- description and source-code
```javascript
registerEngine = function (engineName) {
	var def;

	try {
		def = require('./engines/' + engineName);
		this.engines[engineName] = def;

		debug('Engine "%s": %s v%s installed in %s', engineName, def.name, def.version, def.path);
	} catch (ex) {
		debug('Engine "%s": failed to import - %s', engineName, ex);
	}
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.engines.prototype.run"></a>[function <span class="apidocSignatureSpan">phantomas.engines.prototype.</span>run (scriptFile)](#apidoc.element.phantomas.engines.prototype.run)
- description and source-code
```javascript
run = function (scriptFile) {
	// select the engine
	var engines = this.getEngines(),
		engine = this.getEngine(engines[0]);

	// --engine=[gecko|webkit]
	if (typeof this.options.engine === 'string') {
		engine = this.getEngine(this.options.engine);

		if (typeof engine === 'undefined') {
			throw 'Engine "' + this.options.engine + '" not found!';
		}
	}
	// PHANTOMAS_ENGINE=gecko phantomas "http://example.com"
	else if (typeof process.env.PHANTOMAS_ENGINE === 'string') {
		engine = this.getEngine(process.env.PHANTOMAS_ENGINE);

		if (typeof engine === 'undefined') {
			throw 'Engine "' + process.env.PHANTOMAS_ENGINE + '" not found!';
		}
	}
	// --gecko / --webkit
	else {
		engines.forEach(function(key) {
			if (this.options[key] === true) {
				engine = this.getEngine(key);
			}
		}, this);
	}

	// customize user agent
	if (typeof this.options['user-agent'] === 'undefined') {
		this.options['user-agent'] = "phantomas/" + VERSION + " (" + engine.getUserAgent() + "; " + process.platform + " " + process.arch
 + ")";
	}

	// build engine specific command-line arguments
	var engineArgs = [];

	Object.keys(this.options).forEach(function(key) {
		var val = this.options[key],
			nativeOptions = [
				'cookies-file',
				'debug',
				'ignore-ssl-errors',
				'ssl-protocol',
				'proxy',
				'proxy-auth',
				'proxy-type'
			];

		if (val === false) {
			return;
		}

		// handle native PhantomJS options (#163)
		// @see http://phantomjs.org/api/command-line.html
		if (nativeOptions.indexOf(key) > -1) {
			engineArgs.push('--' + key + '=' + val);
		}
	}, this);

	debug('Running %s (using %s)', scriptFile, engine.name);
	debug('Passing phantomas options: %j', this.options);
	debug('Passing engine options: %j', engineArgs);

	// add a script to run
	engineArgs.push(scriptFile);

	// pass JSON encoded options
	engineArgs.push(JSON.stringify(this.options));

	// spawn the process
	var proc;

	if (typeof engine.spawn === 'function') {
		debug('Using custom spawn function');
		proc = engine.spawn(engine.path, engineArgs);
	} else {
		proc = spawn(engine.path, engineArgs, {
			env: process.env
		});
	}

	return proc;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.fast_stats"></a>[module phantomas.fast_stats](#apidoc.module.phantomas.fast_stats)

#### <a name="apidoc.element.phantomas.fast_stats.Stats"></a>[function <span class="apidocSignatureSpan">phantomas.fast_stats.</span>Stats (c)](#apidoc.element.phantomas.fast_stats.Stats)
- description and source-code
```javascript
function Stats(c) {
	this._config = {
		store_data: true
	};

	if (c) {
		for (var k in config_params) {
			if (c.hasOwnProperty(k)) {
				config_params[k](this, c[k]);
			}
		}
	}

	this.reset();

	return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.ipc"></a>[module phantomas.ipc](#apidoc.module.phantomas.ipc)

#### <a name="apidoc.element.phantomas.ipc.ipc"></a>[function <span class="apidocSignatureSpan">phantomas.</span>ipc (stream)](#apidoc.element.phantomas.ipc.ipc)
- description and source-code
```javascript
function ipc(stream) {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	this.stream = stream;
	this.events = new emitter();

	this.init();
}
```
- example usage
```shell
...
	// emit given event and pass it to CommonJS API via IPC
	emit: function( /* eventName, arg1, arg2, ... */ ) {
		this.emitInternal.apply(this, arguments);

		// pass it via IPC
		var args = Array.prototype.slice.apply(arguments),
			eventName = args.shift(),
			ipc = new this.ipc(eventName);

		ipc.push.apply(ipc, args);
	},

	// emit given event "internally"
	emitInternal: function( /* eventName, arg1, arg2, ... */ ) {
		this.log('Event %s emitted', arguments[0]);
...
```



# <a name="apidoc.module.phantomas.ipc.prototype"></a>[module phantomas.ipc.prototype](#apidoc.module.phantomas.ipc.prototype)

#### <a name="apidoc.element.phantomas.ipc.prototype.init"></a>[function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>init ()](#apidoc.element.phantomas.ipc.prototype.init)
- description and source-code
```javascript
init = function () {
	var self = this,
		buffer = '';

	this.stream.on('data', function(data) {
		buffer += data.toString().trim();

		// check for the separator at the of the buffer - parse the data
		if (buffer.substr(-2) === SEPARATOR) {
			self.parse(buffer);
			buffer = '';
		}
	});
}
```
- example usage
```shell
...
	SEPARATOR = "\xFF\xFF";

function ipc(stream) {
	/* jshint validthis: true */
	this.stream = stream;
	this.events = new emitter();

	this.init();
}

ipc.prototype.setEventEmitter = function(emitter) {
	this.events = emitter;
};

ipc.prototype.init = function() {
...
```

#### <a name="apidoc.element.phantomas.ipc.prototype.on"></a>[function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>on (event, fn)](#apidoc.element.phantomas.ipc.prototype.on)
- description and source-code
```javascript
on = function (event, fn) {
	this.events.on(event, fn);
}
```
- example usage
```shell
...

	this.util = this.require('util');

	this.page = require('webpage').create();

	// store the timestamp of responseEnd event
	// should be bound before modules
	this.on('responseEnd', this.proxy(function() {
		this.responseEndTime = Date.now();
	}));

	// setup logger
	var Logger = require('./logger'),
		logFile = params.log || '';
...
```

#### <a name="apidoc.element.phantomas.ipc.prototype.parse"></a>[function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>parse (data)](#apidoc.element.phantomas.ipc.prototype.parse)
- description and source-code
```javascript
parse = function (data) {
	// split by separator
	data.split(SEPARATOR).forEach(function(msg) {
		msg = msg.trim();

		if (msg === '') return;

		try {
			msg = JSON.parse(msg);
			debug('%s: %j', msg.event, msg.data);

			// send event name and the rest of the data
			var args = msg.data;
			args.unshift(msg.event);

			this.events.emit.apply(this.events, args);

			// send generic "_msg" event for each message received (issue #354)
			this.events.emit('_msg', args);
		} catch (e) {
			// send PhantomJS errors to stderr to ease debugging of issues like #302
			debug('message parsing failed: "%s"', msg);
			process.stderr.write(msg + "\n");
		}
	}, this);
}
```
- example usage
```shell
...
		var prefix, data;

		// split "foo:content"
		prefix = msg.substr(0, 3);
		data = msg.substr(4);

		try {
			data = JSON.parse(data);
		} catch (ex) {
			// fallback to plain log
			prefix = false;
		}

		//console.log(JSON.stringify([prefix, data]));
...
```

#### <a name="apidoc.element.phantomas.ipc.prototype.setEventEmitter"></a>[function <span class="apidocSignatureSpan">phantomas.ipc.prototype.</span>setEventEmitter (emitter)](#apidoc.element.phantomas.ipc.prototype.setEventEmitter)
- description and source-code
```javascript
setEventEmitter = function (emitter) {
	this.events = emitter;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.optimist_config_file"></a>[module phantomas.optimist_config_file](#apidoc.module.phantomas.optimist_config_file)

#### <a name="apidoc.element.phantomas.optimist_config_file.alias"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>alias (x, y)](#apidoc.element.phantomas.optimist_config_file.alias)
- description and source-code
```javascript
alias = function (x, y) {
    if (typeof x === 'object') {
        Object.keys(x).forEach(function (key) {
            self.alias(key, x[key]);
        });
    }
    else {
        options.alias[x] = (options.alias[x] || []).concat(y);
    }
    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.boolean"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>boolean (bools)](#apidoc.element.phantomas.optimist_config_file.boolean)
- description and source-code
```javascript
boolean = function (bools) {
    options.boolean.push.apply(options.boolean, [].concat(bools));
    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.check"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>check (f)](#apidoc.element.phantomas.optimist_config_file.check)
- description and source-code
```javascript
check = function (f) {
    checks.push(f);
    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.default"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>default (key, value)](#apidoc.element.phantomas.optimist_config_file.default)
- description and source-code
```javascript
default = function (key, value) {
    if (typeof key === 'object') {
        Object.keys(key).forEach(function (k) {
            self.default(k, key[k]);
        });
    }
    else {
        options.default[key] = value;
    }
    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.demand"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>demand (keys)](#apidoc.element.phantomas.optimist_config_file.demand)
- description and source-code
```javascript
demand = function (keys) {
    if (typeof keys == 'number') {
        if (!demanded._) demanded._ = 0;
        demanded._ += keys;
    }
    else if (Array.isArray(keys)) {
        keys.forEach(function (key) {
            self.demand(key);
        });
    }
    else {
        demanded[keys] = true;
    }

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.describe"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>describe (opt)](#apidoc.element.phantomas.optimist_config_file.describe)
- description and source-code
```javascript
describe = function (opt) {
	if (nextHeader) {
		headers.push({
			label: nextHeader,
			before: opt
		});
		nextHeader = null;
	}
	return _describe.apply(optimist, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.header"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>header (s)](#apidoc.element.phantomas.optimist_config_file.header)
- description and source-code
```javascript
header = function (s) {
	nextHeader = s;
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.help"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>help ()](#apidoc.element.phantomas.optimist_config_file.help)
- description and source-code
```javascript
help = function () {
	var text = _help.apply(optimist, arguments),
		i, s, p, opt_header = "\nOptions:",
		opt_header_len = opt_header.length;
	//console.log(text,headers);
	for (i = 0; i < headers.length; i++) {
		s = "\n  --" + headers[i].before;
		p = text.indexOf(s);
		if (p != -1) {
			s = "\n" + ansistyles.bright(headers[i].label) + ":";
			text = text.substr(0, p) + s + text.substr(p);
			if (text.substr(p - opt_header_len, opt_header_len) == opt_header) {
				text = text.substr(0, p - opt_header_len) + text.substr(p);
			}
		}
	}
	return text;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.option"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>option (key, opt)](#apidoc.element.phantomas.optimist_config_file.option)
- description and source-code
```javascript
option = function (key, opt) {
    if (typeof key === 'object') {
        Object.keys(key).forEach(function (k) {
            self.options(k, key[k]);
        });
    }
    else {
        if (opt.alias) self.alias(key, opt.alias);
        if (opt.demand) self.demand(key);
        if (typeof opt.default !== 'undefined') {
            self.default(key, opt.default);
        }

        if (opt.boolean || opt.type === 'boolean') {
            self.boolean(key);
        }
        if (opt.string || opt.type === 'string') {
            self.string(key);
        }

        var desc = opt.describe || opt.description || opt.desc;
        if (desc) {
            self.describe(key, desc);
        }
    }

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.options"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>options (key, opt)](#apidoc.element.phantomas.optimist_config_file.options)
- description and source-code
```javascript
options = function (key, opt) {
    if (typeof key === 'object') {
        Object.keys(key).forEach(function (k) {
            self.options(k, key[k]);
        });
    }
    else {
        if (opt.alias) self.alias(key, opt.alias);
        if (opt.demand) self.demand(key);
        if (typeof opt.default !== 'undefined') {
            self.default(key, opt.default);
        }

        if (opt.boolean || opt.type === 'boolean') {
            self.boolean(key);
        }
        if (opt.string || opt.type === 'string') {
            self.string(key);
        }

        var desc = opt.describe || opt.description || opt.desc;
        if (desc) {
            self.describe(key, desc);
        }
    }

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.parse"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>parse (args)](#apidoc.element.phantomas.optimist_config_file.parse)
- description and source-code
```javascript
parse = function (args) {
	var options = origParse(args);
	debug('parse: %j', args);

	// check the config file
	var configFileName = this.configFileParam && options[this.configFileParam],
		configParsed;

	// if --config is not provided, quit
	if (!configFileName) {
		debug('options: %j', options);
		return options;
	}

	configParsed = parseConfigFile(configFileName);

	// apply the rest of the options provided via command line
	Object.keys(configParsed).forEach(function(key) {
		// check if given option was not provided via command line
		if (args.indexOf('--' + key) > -1) {
			debug('--%s option provided via command line, will skip the value from config file', key);
			return;
		}

		options[key] = configParsed[key];
	});

	// cleanup
	delete options[this.configFileParam];

	debug('options: %j', options);
	return options;
}
```
- example usage
```shell
...
		var prefix, data;

		// split "foo:content"
		prefix = msg.substr(0, 3);
		data = msg.substr(4);

		try {
			data = JSON.parse(data);
		} catch (ex) {
			// fallback to plain log
			prefix = false;
		}

		//console.log(JSON.stringify([prefix, data]));
...
```

#### <a name="apidoc.element.phantomas.optimist_config_file.setConfigFile"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>setConfigFile (configFileParam)](#apidoc.element.phantomas.optimist_config_file.setConfigFile)
- description and source-code
```javascript
setConfigFile = function (configFileParam) {
	this.configFileParam = configFileParam;
	return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.showHelp"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>showHelp (fn)](#apidoc.element.phantomas.optimist_config_file.showHelp)
- description and source-code
```javascript
showHelp = function (fn) {
    if (!fn) fn = console.error;
    fn(self.help());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.string"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>string (strings)](#apidoc.element.phantomas.optimist_config_file.string)
- description and source-code
```javascript
string = function (strings) {
    options.string.push.apply(options.string, [].concat(strings));
    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.usage"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>usage (msg, opts)](#apidoc.element.phantomas.optimist_config_file.usage)
- description and source-code
```javascript
usage = function (msg, opts) {
    if (!opts && typeof msg === 'object') {
        opts = msg;
        msg = null;
    }

    usage = msg;

    if (opts) self.options(opts);

    return self;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.optimist_config_file.wrap"></a>[function <span class="apidocSignatureSpan">phantomas.optimist_config_file.</span>wrap (cols)](#apidoc.element.phantomas.optimist_config_file.wrap)
- description and source-code
```javascript
wrap = function (cols) {
    wrap = cols;
    return self;
}
```
- example usage
```shell
...
			}

			res.push('');
		});

		fold.pushEnd(res, 'offenders');

		return fold.wrap(
			results.getUrl(),
			res.join('\n').trim()
		) + '\n';
	}

	function formatMultipleRunResults(results) {
		var AsciiTable = require('ascii-table'),
...
```



# <a name="apidoc.module.phantomas.pads"></a>[module phantomas.pads](#apidoc.module.phantomas.pads)

#### <a name="apidoc.element.phantomas.pads.lpad"></a>[function <span class="apidocSignatureSpan">phantomas.pads.</span>lpad (str, len)](#apidoc.element.phantomas.pads.lpad)
- description and source-code
```javascript
function lpad(str, len) {
	var fill;
	str = typeof str !== 'undefined' ? str : '-';

	fill = new Array(Math.max(1, len - str.toString().length + 1)).join(' ');
	return fill + str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.pads.rpad"></a>[function <span class="apidocSignatureSpan">phantomas.pads.</span>rpad (str, len)](#apidoc.element.phantomas.pads.rpad)
- description and source-code
```javascript
function rpad(str, len) {
	var fill;
	str = typeof str !== 'undefined' ? str : '-';

	fill = new Array(Math.max(1, len - str.toString().length + 1)).join(' ');
	return str + fill;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.phantomas"></a>[module phantomas.phantomas](#apidoc.module.phantomas.phantomas)

#### <a name="apidoc.element.phantomas.phantomas.phantomas"></a>[function <span class="apidocSignatureSpan">phantomas.</span>phantomas (params)](#apidoc.element.phantomas.phantomas.phantomas)
- description and source-code
```javascript
phantomas = function (params) {
	var fs = require('fs');

	// store script CLI parameters
	this.params = params;

	// --url=http://example.com
	this.url = params.url;

	// --format
	this.format = params.format;

	// --verbose
	this.verboseMode = params.verbose === true;

	// --silent
	this.silentMode = params.silent === true;

	// --timeout (in seconds)
	this.timeout = (params.timeout > 0 && parseInt(params.timeout, 10)) || 15;

	// --modules=localStorage,cookies
	this.modules = (typeof params.modules === 'string') ? params.modules.split(',') : [];

	// --include-dirs=dirOne,dirTwo
	this.includeDirs = (typeof params['include-dirs'] === 'string') ? params['include-dirs'].split(',') : [];

	// --skip-modules=jQuery,domQueries
	this.skipModules = (typeof params['skip-modules'] === 'string') ? params['skip-modules'].split(',') : [];

	// disable JavaScript on the page that will be loaded
	this.disableJs = params['disable-js'] === true;

	// setup the stuff
	this.emitter = new(this.require('events').EventEmitter)();
	this.emitter.setMaxListeners(200);
	this.ipc = require('./ipc');

	this.util = this.require('util');

	this.page = require('webpage').create();

	// store the timestamp of responseEnd event
	// should be bound before modules
	this.on('responseEnd', this.proxy(function() {
		this.responseEndTime = Date.now();
	}));

	// setup logger
	var Logger = require('./logger'),
		logFile = params.log || '';

	this.logger = new Logger(logFile, {
		beVerbose: this.verboseMode,
		beSilent: this.silentMode
	});

	// detect phantomas working directory
	if (typeof module.dirname !== 'undefined') {
		this.dir = module.dirname.replace(/core$/, '');
	} else if (typeof slimer !== 'undefined') {
		var args = require('system').args;
		this.dir = fs.dirname(args[0]).replace(/scripts$/, '');
	}

	this.log('phantomas v%s: %s', this.getVersion(), this.dir);
	this.log('Options: %j', this.params);

	// queue of jobs that needs to be done before report can be generated
	var Queue = require('../lib/simple-queue');
	this.reportQueue = new Queue();

	// set up results wrapper
	var Results = require('./results');
	this.results = new Results();

	this.results.setGenerator('phantomas v' + this.getVersion());
	this.results.setUrl(this.url);

	this.metricsAvgStorage = {};

	// allow asserts to be provided via command-line options (#128)
	Object.keys(this.params).forEach(function(param) {
		var value = parseFloat(this.params[param]),
			name;

		if (!isNaN(value) && param.indexOf('assert-') === 0) {
			name = param.substr(7);

			if (name.length > 0) {
				this.results.setAssert(name, value);
			}
		}
	}, this);

	// load core modules
	this.log('Loading: core modules...');
	this.addCoreModule('navigationTiming');
	this.addCoreModule('requestsMonitor');
	this.addCoreModule('timeToFirstByte');

	// load extensions
	this.log('Loading: extensions...');
	var extensions = this.listExtensions();
	extensions.forEach(this.addExtension, this);

	// load modules
	this.log('Loading: modules...');
	var modules = (this.modules.length > 0) ? this.modules : this.listModules();
	modules.forEach(this.addModule, this);

	// load 3rd party modules
	this.log('Loading: 3rd party modules...');
	this.includeDirs.forEach(function(dirName) {
		var dirPath = fs.absolute(dirName),
			dirModules = this.listModulesInDir(dirPath);

		dirModules.forEach(function(moduleName) {
			this.addModuleInDir(dirPath, moduleName);
		}, this);

	}, this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.phantomas.prototype"></a>[module phantomas.phantomas.prototype](#apidoc.module.phantomas.phantomas.prototype)

#### <a name="apidoc.element.phantomas.phantomas.prototype.addCoreModule"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addCoreModule (name)](#apidoc.element.phantomas.phantomas.prototype.addCoreModule)
- description and source-code
```javascript
addCoreModule = function (name) {
		var pkg = require('./modules/' + name + '/' + name);

		// init a module
		pkg.module(this.getPublicWrapper());

		this.log('Core module %s%s initialized', name, (pkg.version ? ' v' + pkg.version : ''));
	}
```
- example usage
```shell
...
				this.results.setAssert(name, value);
			}
		}
	}, this);

	// load core modules
	this.log('Loading: core modules...');
	this.addCoreModule('navigationTiming');
	this.addCoreModule('requestsMonitor');
	this.addCoreModule('timeToFirstByte');

	// load extensions
	this.log('Loading: extensions...');
	var extensions = this.listExtensions();
	extensions.forEach(this.addExtension, this);
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.addExtension"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addExtension (name)](#apidoc.element.phantomas.phantomas.prototype.addExtension)
- description and source-code
```javascript
addExtension = function (name) {
		return this.addModuleInDir('./../extensions', name);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.addModule"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addModule (name)](#apidoc.element.phantomas.phantomas.prototype.addModule)
- description and source-code
```javascript
addModule = function (name) {
		return this.addModuleInDir('./../modules', name);
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.addModuleInDir"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addModuleInDir (dir, name)](#apidoc.element.phantomas.phantomas.prototype.addModuleInDir)
- description and source-code
```javascript
addModuleInDir = function (dir, name) {
		var pkg;
		if (this.skipModules.indexOf(name) > -1) {
			this.log('Module %s skipped!', name);
			return;
		}
		try {
			pkg = require(dir + '/' + name + '/' + name);
		} catch (e) {
			this.log('Unable to load module "%s" from %s!', name, dir);
			this.log('%s!', e);
			return false;
		}

		if (pkg.skip) {
			this.log('Module %s skipped!', name);
			return false;
		}

		// init a module
		pkg.module(this.getPublicWrapper());

		this.log('Module %s%s initialized', name, (pkg.version ? ' v' + pkg.version : ''));
		return true;
	}
```
- example usage
```shell
...
	// load 3rd party modules
	this.log('Loading: 3rd party modules...');
	this.includeDirs.forEach(function(dirName) {
		var dirPath = fs.absolute(dirName),
			dirModules = this.listModulesInDir(dirPath);

		dirModules.forEach(function(moduleName) {
			this.addModuleInDir(dirPath, moduleName);
		}, this);

	}, this);
};

phantomas.version = VERSION;
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.addOffender"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addOffender ()](#apidoc.element.phantomas.phantomas.prototype.addOffender)
- description and source-code
```javascript
addOffender = function () {
		var args = Array.prototype.slice.call(arguments),
			metricName = args.shift();

		this.results.addOffender(metricName, this.util.format.apply(this, args));
	}
```
- example usage
```shell
...

					self.log('Timeout: gave up waiting for %d HTTP response(s): <%s>', currentRequests, timedOutRequests.join('>, <'));

					// emit timed out requests as a fake metric (#539)
					self.results.setMetric('requestsWithTimeout', timedOutRequests.length);

					timedOutRequests.forEach(function(url) {
						self.results.addOffender('requestsWithTimeout', url);
					});
				});

				// always register the metric (issue #581)
				self.results.setMetric('requestsWithTimeout', 0);
			});
		}
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.addToAvgMetric"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>addToAvgMetric (name, value)](#apidoc.element.phantomas.phantomas.prototype.addToAvgMetric)
- description and source-code
```javascript
addToAvgMetric = function (name, value) {
		if (typeof this.metricsAvgStorage[name] === 'undefined') {
			this.metricsAvgStorage[name] = [];
		}

		this.metricsAvgStorage[name].push(value);

		this.setMetric(name, getAverage(this.metricsAvgStorage[name]));
	}
```
- example usage
```shell
...
				break;

			case 'incrMetric':
				this.incrMetric(data.name, data.incr);
				break;

			case 'addToAvgMetric':
				this.addToAvgMetric(data.name, data.value);
				break;

			case 'setMarkerMetric':
				this.setMarkerMetric(data.name);
				break;

			case 'addOffender':
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.echo"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>echo (msg)](#apidoc.element.phantomas.phantomas.prototype.echo)
- description and source-code
```javascript
echo = function (msg) {
		this.logger.echo(msg);
	}
```
- example usage
```shell
...
	// supports phantomas.log('foo: <%s>', url);
	log: function() {
		this.logger.log(this.util.format.apply(this, arguments));
	},

	// console.log wrapper obeying --silent mode
	echo: function(msg) {
		this.logger.echo(msg);
	},

	// require CommonJS module from lib/modules
	require: function(module) {
		return require('../lib/modules/' + module);
	},
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.emit"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>emit ()](#apidoc.element.phantomas.phantomas.prototype.emit)
- description and source-code
```javascript
emit = function () {
		this.emitInternal.apply(this, arguments);

		// pass it via IPC
		var args = Array.prototype.slice.apply(arguments),
			eventName = args.shift(),
			ipc = new this.ipc(eventName);

		ipc.push.apply(ipc, args);
	}
```
- example usage
```shell
...

			// store the change and update the current progress
			inc = this.page.loadingProgress - currentProgress;
			currentProgress = this.page.loadingProgress;

			this.log('Loading progress: %d%', currentProgress);

			this.emit('progress', currentProgress, inc); // @desc loading progress has changed
		}

		if (typeof this.page.loadingProgress !== 'undefined') {
			setInterval(pollFn.bind(this), 50);
		} else {
			this.log('Loading progress: not available!');
		}
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.emitInternal"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>emitInternal ()](#apidoc.element.phantomas.phantomas.prototype.emitInternal)
- description and source-code
```javascript
emitInternal = function () {
		this.log('Event %s emitted', arguments[0]);
		this.emitter.emit.apply(this.emitter, arguments);
	}
```
- example usage
```shell
...
			self.on('loadFinished', done);
		});

		// generate a report when all jobs are done
		this.reportQueue.done(this.report, this);

		// last time changes?
		this.emitInternal('pageBeforeOpen', this.page); // @desc page.open is about to be called

		// open the page
		this.page.open(this.url);

		this.emitInternal('pageOpen'); // @desc page.open has been called

		// fallback - always timeout after TIMEOUT seconds
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.getMetric"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getMetric (name)](#apidoc.element.phantomas.phantomas.prototype.getMetric)
- description and source-code
```javascript
getMetric = function (name) {
		return this.results.getMetric(name);
	}
```
- example usage
```shell
...

		this.setMetric(name, value, true /* isFinal */ );
		return value;
	},

	// increements given metric by given number (default is one)
	incrMetric: function(name, incr /* =1 */ ) {
		var currVal = this.getMetric(name) || 0;
		this.setMetric(name, currVal + (typeof incr === 'number' ? incr : 1));
	},

	// push a value and update the metric if the current average value
	addToAvgMetric: function(name, value) {
		if (typeof this.metricsAvgStorage[name] === 'undefined') {
			this.metricsAvgStorage[name] = [];
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.getParam"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getParam (key, defValue, typeCheck)](#apidoc.element.phantomas.phantomas.prototype.getParam)
- description and source-code
```javascript
getParam = function (key, defValue, typeCheck) {
		var value = this.params[key];

		// strict type check
		if (typeof typeCheck === 'string' && typeof value !== typeCheck) {
			value = undefined;
		}

		return value || defValue;
	}
```
- example usage
```shell
...
		}

		this.start = Date.now();

		var self = this;

		// setup viewport / --viewport=1366x768
		var parsedViewport = this.getParam('viewport', '1366x768', 'string').split('x');

		if (parsedViewport.length === 2) {
			var viewportSize = {
				width: parseInt(parsedViewport[0], 10) || 1366,
				height: parseInt(parsedViewport[1], 10) || 768
			};
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.getPublicWrapper"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getPublicWrapper ()](#apidoc.element.phantomas.phantomas.prototype.getPublicWrapper)
- description and source-code
```javascript
getPublicWrapper = function () {
		function setParam(key, value) {
			<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>			this.log('setParam: %s set to %j', key, value);
			this.params[key] = value;
		}

		function setZoom(zoomFactor) {
			/* jshint validthis: true */
			this.page.zoomFactor = zoomFactor;
		}

		// modules API
		return {
			url: this.params.url,
			getVersion: this.getVersion.bind(this),
			getParam: this.getParam.bind(this),
			setParam: setParam.bind(this),

			// events
			on: this.on.bind(this),
			once: this.once.bind(this),
			emit: this.emit.bind(this),
			emitInternal: this.emitInternal.bind(this),

			// reports
			reportQueuePush: this.reportQueue.push.bind(this.reportQueue),

			// metrics
			setMetric: this.setMetric.bind(this),
			setMetricEvaluate: this.setMetricEvaluate.bind(this),
			setMarkerMetric: this.setMarkerMetric.bind(this),
			incrMetric: this.incrMetric.bind(this),
			addToAvgMetric: this.addToAvgMetric.bind(this),
			getMetric: this.getMetric.bind(this),

			// offenders
			addOffender: this.addOffender.bind(this),

			// debug
			log: this.log.bind(this),
			echo: this.echo.bind(this),

			// phantomJS
			evaluate: this.page.evaluate.bind(this.page),
			injectJs: this.page.injectJs.bind(this.page),
			require: this.require.bind(this),
			render: this.page.render.bind(this.page),
			setZoom: setZoom.bind(this),
			getSource: this.getSource.bind(this),

			// utils
			runScript: this.runScript.bind(this),
			tmpdir: this.tmpdir.bind(this)
		};
	}
```
- example usage
```shell
...
	},

	// initialize given core phantomas module
	addCoreModule: function(name) {
		var pkg = require('./modules/' + name + '/' + name);

		// init a module
		pkg.module(this.getPublicWrapper());

		this.log('Core module %s%s initialized', name, (pkg.version ? ' v' + pkg.version : ''));
	},

	// initialize given phantomas extension
	addExtension: function(name) {
		return this.addModuleInDir('./../extensions', name);
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.getSource"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getSource ()](#apidoc.element.phantomas.phantomas.prototype.getSource)
- description and source-code
```javascript
getSource = function () {
		return this.page.content;
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.getVersion"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>getVersion ()](#apidoc.element.phantomas.phantomas.prototype.getVersion)
- description and source-code
```javascript
getVersion = function () {
		return VERSION;
	}
```
- example usage
```shell
...
	if (typeof module.dirname !== 'undefined') {
		this.dir = module.dirname.replace(/core$/, '');
	} else if (typeof slimer !== 'undefined') {
		var args = require('system').args;
		this.dir = fs.dirname(args[0]).replace(/scripts$/, '');
	}

	this.log('phantomas v%s: %s', this.getVersion(), this.dir);
	this.log('Options: %j', this.params);

	// queue of jobs that needs to be done before report can be generated
	var Queue = require('../lib/simple-queue');
	this.reportQueue = new Queue();

	// set up results wrapper
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.incrMetric"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>incrMetric (name, incr)](#apidoc.element.phantomas.phantomas.prototype.incrMetric)
- description and source-code
```javascript
incrMetric = function (name, incr) {
		var currVal = this.getMetric(name) || 0;
		this.setMetric(name, currVal + (typeof incr === 'number' ? incr : 1));
	}
```
- example usage
```shell
...
				break;

			case 'setMetric':
				this.setMetric(data.name, data.value, data.isFinal);
				break;

			case 'incrMetric':
				this.incrMetric(data.name, data.incr);
				break;

			case 'addToAvgMetric':
				this.addToAvgMetric(data.name, data.value);
				break;

			case 'setMarkerMetric':
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.initLoadingProgress"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>initLoadingProgress ()](#apidoc.element.phantomas.phantomas.prototype.initLoadingProgress)
- description and source-code
```javascript
initLoadingProgress = function () {
		var currentProgress = false;

		function pollFn() {
			<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>			var inc;

			if (currentProgress >= this.page.loadingProgress) {
				return;
			}

			// store the change and update the current progress
			inc = this.page.loadingProgress - currentProgress;
			currentProgress = this.page.loadingProgress;

			this.log('Loading progress: %d%', currentProgress);

			this.emit('progress', currentProgress, inc); // @desc loading progress has changed
		}

		if (typeof this.page.loadingProgress !== 'undefined') {
			setInterval(pollFn.bind(this), 50);
		} else {
			this.log('Loading progress: not available!');
		}
	}
```
- example usage
```shell
...
		this.page.onAlert = this.proxy(this.onAlert);
		this.page.onConfirm = this.proxy(this.onConfirm);
		this.page.onPrompt = this.proxy(this.onPrompt);
		this.page.onConsoleMessage = this.proxy(this.onConsoleMessage);
		this.page.onCallback = this.proxy(this.onCallback);
		this.page.onError = this.proxy(this.onError);

		this.initLoadingProgress();

		// do not wait for any requests, stop immediately after onload event (issue #513)
		if (this.getParam('stop-at-onload', false) === true) {
			this.log('stop-at-onload: --stop-at-onload passed, will stop immediately after onload event');
		} else {
			// observe HTTP requests
			// finish when the last request is completed + one second timeout
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.listExtensions"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listExtensions ()](#apidoc.element.phantomas.phantomas.prototype.listExtensions)
- description and source-code
```javascript
listExtensions = function () {
		return this.listModulesInDir(this.dir + 'extensions');
	}
```
- example usage
```shell
...
	this.log('Loading: core modules...');
	this.addCoreModule('navigationTiming');
	this.addCoreModule('requestsMonitor');
	this.addCoreModule('timeToFirstByte');

	// load extensions
	this.log('Loading: extensions...');
	var extensions = this.listExtensions();
	extensions.forEach(this.addExtension, this);

	// load modules
	this.log('Loading: modules...');
	var modules = (this.modules.length > 0) ? this.modules : this.listModules();
	modules.forEach(this.addModule, this);
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.listModules"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listModules ()](#apidoc.element.phantomas.phantomas.prototype.listModules)
- description and source-code
```javascript
listModules = function () {
		return this.listModulesInDir(this.dir + 'modules');
	}
```
- example usage
```shell
...
	// load extensions
	this.log('Loading: extensions...');
	var extensions = this.listExtensions();
	extensions.forEach(this.addExtension, this);

	// load modules
	this.log('Loading: modules...');
	var modules = (this.modules.length > 0) ? this.modules : this.listModules();
	modules.forEach(this.addModule, this);

	// load 3rd party modules
	this.log('Loading: 3rd party modules...');
	this.includeDirs.forEach(function(dirName) {
		var dirPath = fs.absolute(dirName),
			dirModules = this.listModulesInDir(dirPath);
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.listModulesInDir"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>listModulesInDir (modulesDir)](#apidoc.element.phantomas.phantomas.prototype.listModulesInDir)
- description and source-code
```javascript
listModulesInDir = function (modulesDir) {
		this.log('Getting the list of all modules in %s...', modulesDir);

		var fs = require('fs'),
			ls = fs.list(modulesDir) || [],
			modules = [];

		ls.forEach(function(entry) {
			<span class="apidocCodeCommentSpan">/**
			 * README.md will be listed as an entry. That caused issue #409:
			 * SlimerJS raised: "Component returned failure code: 0x80520005 (NS_ERROR_FILE_DESTINATION_NOT_DIR) [nsILocalFile.isFile]"
			 *
			 * First check whether an entry is a directory, than check if it contains a module file
			 */
</span>			if (fs.isDirectory(modulesDir + '/' + entry) && fs.isFile(modulesDir + '/' + entry + '/' + entry + '.js')) {
				modules.push(entry);
			}
		});

		// SlimerJS 'fs.list' does not order the returned array
		// PhantomJS does that, so be consistent here :)
		return modules.sort();
	}
```
- example usage
```shell
...
	var modules = (this.modules.length > 0) ? this.modules : this.listModules();
	modules.forEach(this.addModule, this);

	// load 3rd party modules
	this.log('Loading: 3rd party modules...');
	this.includeDirs.forEach(function(dirName) {
		var dirPath = fs.absolute(dirName),
			dirModules = this.listModulesInDir(dirPath);

		dirModules.forEach(function(moduleName) {
			this.addModuleInDir(dirPath, moduleName);
		}, this);

	}, this);
};
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.log"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>log ()](#apidoc.element.phantomas.phantomas.prototype.log)
- description and source-code
```javascript
log = function () {
		this.logger.log(this.util.format.apply(this, arguments));
	}
```
- example usage
```shell
...

		// set up a stream to be used for logging
		stream = fs.open(logFile, 'w');
	}

	function echo(msg) {
		if (!beSilent) {
			console.log(msg);
		}
	}

	function log(msg) {
		var ts = (new Date()).toJSON().substr(11, 12);

		// format a message
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.on"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>on (ev, fn)](#apidoc.element.phantomas.phantomas.prototype.on)
- description and source-code
```javascript
on = function (ev, fn) {
		this.emitter.on(ev, fn);
	}
```
- example usage
```shell
...

	this.util = this.require('util');

	this.page = require('webpage').create();

	// store the timestamp of responseEnd event
	// should be bound before modules
	this.on('responseEnd', this.proxy(function() {
		this.responseEndTime = Date.now();
	}));

	// setup logger
	var Logger = require('./logger'),
		logFile = params.log || '';
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onAlert"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onAlert (msg)](#apidoc.element.phantomas.phantomas.prototype.onAlert)
- description and source-code
```javascript
onAlert = function (msg) {
		this.log('Alert: %s', msg);
		this.emitInternal('alert', msg); // @desc the page called window.alert
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onCallback"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onCallback (msg)](#apidoc.element.phantomas.phantomas.prototype.onCallback)
- description and source-code
```javascript
onCallback = function (msg) {
		var type = msg && msg.type || '',
			data = msg && msg.data || {};

		switch (type) {
			case 'log':
				this.log.apply(this, data);
				break;

			case 'setMetric':
				this.setMetric(data.name, data.value, data.isFinal);
				break;

			case 'incrMetric':
				this.incrMetric(data.name, data.incr);
				break;

			case 'addToAvgMetric':
				this.addToAvgMetric(data.name, data.value);
				break;

			case 'setMarkerMetric':
				this.setMarkerMetric(data.name);
				break;

			case 'addOffender':
				this.addOffender.apply(this, data);
				break;

			case 'emit':
				this.emit.apply(this, data);
				break;

			default:
				this.log('Message "%s" from browser\'s scope: %j', type, data);
				this.emitInternal('message', msg); // @desc the scope script sent a message
		}
	}
```
- example usage
```shell
...
		}

		//console.log(JSON.stringify([prefix, data]));

		switch (prefix) {
			// handle JSON-encoded messages from browser's scope sendMsg()
			case 'msg':
				this.onCallback(data);
				break;

				// console.log arguments are passed as JSON-encoded array
			case 'log':
				msg = this.util.format.apply(this, data);

				this.log('console.log: %s', msg);
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onConfirm"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onConfirm (msg)](#apidoc.element.phantomas.phantomas.prototype.onConfirm)
- description and source-code
```javascript
onConfirm = function (msg) {
		this.log('Confirm: %s', msg);
		this.emitInternal('confirm', msg); // @desc the page called window.confirm
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onConsoleMessage"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onConsoleMessage (msg)](#apidoc.element.phantomas.phantomas.prototype.onConsoleMessage)
- description and source-code
```javascript
onConsoleMessage = function (msg) {
		var prefix, data;

		// split "foo:content"
		prefix = msg.substr(0, 3);
		data = msg.substr(4);

		try {
			data = JSON.parse(data);
		} catch (ex) {
			// fallback to plain log
			prefix = false;
		}

		//console.log(JSON.stringify([prefix, data]));

		switch (prefix) {
			// handle JSON-encoded messages from browser's scope sendMsg()
			case 'msg':
				this.onCallback(data);
				break;

				// console.log arguments are passed as JSON-encoded array
			case 'log':
				msg = this.util.format.apply(this, data);

				this.log('console.log: %s', msg);
				this.emitInternal('consoleLog', msg, data); // @desc the page called console.log
				break;

			default:
				this.log(msg);
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onError"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onError (msg, trace)](#apidoc.element.phantomas.phantomas.prototype.onError)
- description and source-code
```javascript
onError = function (msg, trace) {
		this.log('JS error: %s', msg);
		this.emitInternal('jserror', msg, trace); // @desc JS error occured
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onInitialized"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onInitialized ()](#apidoc.element.phantomas.phantomas.prototype.onInitialized)
- description and source-code
```javascript
onInitialized = function () {
		// SlimerJS triggers this event twice
		// @see https://github.com/laurentj/slimerjs/blob/master/docs/api/webpage.rst#oninitialized
		if (this.page.url === '') {
			this.log('onInit: webpage.url is empty, waiting for the second trigger...');
			return;
		}

		var currentUrl = this.page.url;

		// prevent multiple triggers in PhantomJS
		// but only on the same page (issue #550)
		if (this.initTriggered === currentUrl) {
			this.log('onInit: was already triggered for <%s>', currentUrl);
			return;
		}
		this.initTriggered = currentUrl;

		// Another multiple triggers case in PhantomJS (issue #606)
		if (this.page.url === 'about:blank') {
			this.log('onInit: webpage.url is about:blank, ignoring');
			return;
		}

		// add helper tools into window.__phantomas "namespace"
		if (!this.page.injectJs(this.dir + 'core/scope.js')) {
			this.tearDown(EXIT_ERROR, 'Scope script injection failed');
			return;
		}

		this.log('onInit: page object initialized');
		this.emitInternal('init'); // @desc page has been initialized, scripts can be injected
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onLoadFinished"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onLoadFinished (status)](#apidoc.element.phantomas.phantomas.prototype.onLoadFinished)
- description and source-code
```javascript
onLoadFinished = function (status) {
		// trigger this only once
		if (this.onLoadFinishedEmitted) {
			return;
		}
		this.onLoadFinishedEmitted = true;

		// we're done
		this.log('Page loading finished ("%s")', status);

		switch (status) {
			case 'success':
				this.emitInternal('loadFinished', status); // @desc page has been fully loaded
				break;

			default:
				this.emitInternal('loadFailed', status); // @desc page loading failed
				this.tearDown(EXIT_LOAD_FAILED, 'Page loading failed');
				break;
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onLoadStarted"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onLoadStarted (url, isFrame)](#apidoc.element.phantomas.phantomas.prototype.onLoadStarted)
- description and source-code
```javascript
onLoadStarted = function (url, isFrame) {
		if (this.onLoadStartedEmitted) {
			return;
		}

		// onLoadStarted is called for the page and each iframe
		// tigger "loadStarted" event just once
		this.onLoadStartedEmitted = true;

		this.log('Page loading started');
		this.emitInternal('loadStarted'); // @desc page loading has started
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onPrompt"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onPrompt (msg)](#apidoc.element.phantomas.phantomas.prototype.onPrompt)
- description and source-code
```javascript
onPrompt = function (msg) {
		this.log('Prompt: %s', msg);
		this.emitInternal('prompt', msg); // @desc the page called window.prompt
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onResourceReceived"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onResourceReceived (res)](#apidoc.element.phantomas.phantomas.prototype.onResourceReceived)
- description and source-code
```javascript
onResourceReceived = function (res) {
		this.emitInternal('onResourceReceived', res); // @desc HTTP response has been received
		//this.log(JSON.stringify(res));
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.onResourceRequested"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>onResourceRequested (res, request)](#apidoc.element.phantomas.phantomas.prototype.onResourceRequested)
- description and source-code
```javascript
onResourceRequested = function (res, request) {
		this.emitInternal('onResourceRequested', res, request); // @desc HTTP request has been sent
		//this.log(JSON.stringify(res));
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.once"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>once (ev, fn)](#apidoc.element.phantomas.phantomas.prototype.once)
- description and source-code
```javascript
once = function (ev, fn) {
		this.emitter.once(ev, fn);
	}
```
- example usage
```shell
...

	// bind to a given event
	on: function(ev, fn) {
		this.emitter.on(ev, fn);
	},

	once: function(ev, fn) {
		this.emitter.once(ev, fn);
	},

	getVersion: function() {
		return VERSION;
	},

	getParam: function(key, defValue, typeCheck) {
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.proxy"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>proxy (fn, scope)](#apidoc.element.phantomas.phantomas.prototype.proxy)
- description and source-code
```javascript
proxy = function (fn, scope) {
		scope = scope || this;
		return function() {
			return fn.apply(scope, arguments);
		};
	}
```
- example usage
```shell
...

	this.util = this.require('util');

	this.page = require('webpage').create();

	// store the timestamp of responseEnd event
	// should be bound before modules
	this.on('responseEnd', this.proxy(function() {
		this.responseEndTime = Date.now();
	}));

	// setup logger
	var Logger = require('./logger'),
		logFile = params.log || '';
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.report"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>report ()](#apidoc.element.phantomas.phantomas.prototype.report)
- description and source-code
```javascript
report = function () {
		// restote the native JSON.parse (just in case, see #482)
		this.page.evaluate(function() {
			JSON.parse = window.__phantomas && window.__phantomas.JSON.parse;
		});

		this.emitInternal('report'); // @desc the report is about to be generated

		var time = Date.now() - this.start;
		this.log('phantomas run for <%s> completed in %d ms', this.page.url, time);

		this.results.setUrl(this.page.url);
		this.emitInternal('results', this.results); // @desc modify the results

		// count all metrics
		this.log('Returning results with %d metric(s)...', this.results.getMetricsNames().length);

		// emit results in JSON
		var formatter = require('./formatter');
		this.emit('json', formatter(this.results));

		// handle timeouts (issue #129)
		if (this.timedOut) {
			this.tearDown(EXIT_TIMED_OUT, 'Timeout');
			return;
		}

		// asserts handling
		var failedAsserts = this.results.getFailedAsserts(),
			failedAssertsCnt = failedAsserts.length;

		if (failedAssertsCnt > 0) {
			this.log('Failed on %d assert(s) on the following metric(s): %s!', failedAssertsCnt, failedAsserts.join(', '));

			// exit code should equal number of failed assertions
			this.tearDown(failedAssertsCnt);
			return;
		}

		this.log('Done!');
		this.tearDown();
	}
```
- example usage
```shell
...
		this.log('Timeout set to %d sec', this.timeout);
		setTimeout(function() {
			this.log('Timeout of %d sec was reached!', this.timeout);

			this.emitInternal('timeout'); // @desc phantomas has timed out
			this.timedOut = true;

			this.report();
		}.bind(this), this.timeout * 1000);
	},

	// called when all HTTP requests are completed
	report: function() {
		// restote the native JSON.parse (just in case, see #482)
		this.page.evaluate(function() {
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.require"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>require (module)](#apidoc.element.phantomas.phantomas.prototype.require)
- description and source-code
```javascript
require = function (module) {
		return require('../lib/modules/' + module);
	}
```
- example usage
```shell
...
	// --skip-modules=jQuery,domQueries
	this.skipModules = (typeof params['skip-modules'] === 'string') ? params['skip-modules'].split(',') : [];

	// disable JavaScript on the page that will be loaded
	this.disableJs = params['disable-js'] === true;

	// setup the stuff
	this.emitter = new(this.require('events').EventEmitter)();
	this.emitter.setMaxListeners(200);
	this.ipc = require('./ipc');

	this.util = this.require('util');

	this.page = require('webpage').create();
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.run"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>run ()](#apidoc.element.phantomas.phantomas.prototype.run)
- description and source-code
```javascript
run = function () {
		// check required params
		if (!this.url) {
			throw '--url argument must be provided!';
		}

		this.start = Date.now();

		var self = this;

		// setup viewport / --viewport=1366x768
		var parsedViewport = this.getParam('viewport', '1366x768', 'string').split('x');

		if (parsedViewport.length === 2) {
			var viewportSize = {
				width: parseInt(parsedViewport[0], 10) || 1366,
				height: parseInt(parsedViewport[1], 10) || 768
			};

			this.page.viewportSize = viewportSize;

			this.on('init', function() {
				self.page.evaluate(function(viewportSize) {
					try {
						window.screen = {
							width: viewportSize.width,
							height: viewportSize.height,
							availWidth: viewportSize.width,
							availHeight: viewportSize.height,
							availLeft: 0,
							availTop: 0,
							colorDepth: 24,
							pixelDepth: 24
						};
					} catch (ex) {
						// SlimmerJS complains: "Error: setting a property that has only a getter"
					}
				}, viewportSize);
			});
		}

		// setup user agent /  --user-agent=custom-agent
		this.page.settings.userAgent = this.getParam('user-agent');

		// disable JavaScript on the page that will be loaded
		if (this.disableJs) {
			this.page.settings.javascriptEnabled = false;
			this.log('JavaScript execution disabled by --disable-js!');
		}

		// print out debug messages
		this.log('Opening <%s>...', this.url);
		this.log('Using %s as user agent', this.page.settings.userAgent);
		this.log('Viewport set to %d x %d', this.page.viewportSize.width, this.page.viewportSize.height);

		// bind basic events
		this.page.onInitialized = this.proxy(this.onInitialized);
		this.page.onLoadStarted = this.proxy(this.onLoadStarted);
		this.page.onLoadFinished = this.proxy(this.onLoadFinished);
		this.page.onResourceRequested = this.proxy(this.onResourceRequested);
		this.page.onResourceReceived = this.proxy(this.onResourceReceived);

		// debug
		this.page.onAlert = this.proxy(this.onAlert);
		this.page.onConfirm = this.proxy(this.onConfirm);
		this.page.onPrompt = this.proxy(this.onPrompt);
		this.page.onConsoleMessage = this.proxy(this.onConsoleMessage);
		this.page.onCallback = this.proxy(this.onCallback);
		this.page.onError = this.proxy(this.onError);

		this.initLoadingProgress();

		// do not wait for any requests, stop immediately after onload event (issue #513)
		if (this.getParam('stop-at-onload', false) === true) {
			this.log('stop-at-onload: --stop-at-onload passed, will stop immediately after onload event');
		} else {
			// observe HTTP requests
			// finish when the last request is completed + one second timeout
			this.reportQueue.push(function(done) {
				var currentRequests = 0,
					requestsUrls = {},
					onFinished = function(entry) {
						currentRequests--;
						delete requestsUrls[entry.url];

						if (currentRequests < 1) {
							timeoutId = setTimeout(function() {
								done();
							}, 1000);
						}
					},
					timeoutId;

				// update HTTP requests counter
				self.on('send', function(entry) {
					clearTimeout(timeoutId);

					currentRequests++;
					requestsUrls[entry.url] = true;
				});

				self.on('recv', onFinished);
				self.on('abort', onFinished);

				// add debug info about pending responses (issue #216)
				self.on('timeout', function() {
					var timedOutRequests = Object.keys(requestsUrls);

					self.log('Timeout: gave up waiting for %d HTTP response(s): <%s>', currentRequests, timedOutRequests.join('>, <'));

					// emit timed out requests as a fake metric (#539)
					self.results.setMetric('requestsWithTimeout', timedOutRequests.length);

					timedOutRequests.forEach(function(url) {
						self.results.addOffender('requestsWithTimeout', url);
					});
				});

				// always register the metric (issue #581)
				self.results.setMetric('requestsWithTimeout', 0);
			});
		}

		this.reportQueue.push(function(done) {
			self.on('loadFinished', done);
		});

		// generate a report when all jobs are done
		this.reportQueue.done(this.report, this);

		// last time changes?
		this.emitInternal('pageBeforeOpen', this.page); // @desc page.open ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.runScript"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>runScript (script, args, callback)](#apidoc.element.phantomas.phantomas.prototype.runScript)
- description and source-code
```javascript
runScript = function (script, args, callback) {
		var execFile = require("child_process").execFile,
			fs = require('fs'),
			osName = require('system').os.name, // linux / windows
			start = Date.now(),
			self = this;

		if (typeof args === 'function') {
			callback = args;
		}

		// execFile(file, args, options, callback)
		// @see https://github.com/ariya/phantomjs/wiki/API-Reference-ChildProcess
		args = args || [];

		// handle relative paths to binaries (issue #672)
		if (!fs.isAbsolute(script)) {
			script = this.dir + script;
		}

		// Windows fix: escape '&' (#587)
		// @see http://superuser.com/questions/550048/is-there-an-escape-for-character-in-the-command-prompt
		if (osName === 'windows') {
			args = args.map(function(arg) {
				return arg.replace(/&/g, '^^^$&'); // $& - Inserts the matched substring
			});
		}

		// always wait for runScript to finish (issue #417)
		this.reportQueue.push(function(done) {
			var ctx, pid;

			ctx = execFile(script, args, null, function(err, stdout, stderr) {
				var time = Date.now() - start;
				var result = stderr !== "" ? stderr : stdout;

				if (err || stderr) {
					var errMessage = (err || stderr || 'unknown error').trim();
					self.log('runScript: pid #%d failed - %s (took %d ms)!', pid, errMessage, time);

					callback(errMessage, result);

					done();
					return;
				} else if (!pid) {
					self.log('runScript: failed running %s %s!', script, args.join(' '));

					done();
					return;
				} else {
					self.log('runScript: pid #%d done (took %d ms)', pid, time);
				}

				// (try to) parse JSON-encoded output
				try {
					result = JSON.parse(stdout);
				} catch (ex) {
					self.log('runScript: JSON parsing failed! - %s', ex);
					err = ex;
				}

				callback(err, result);

				done();
			});

			pid = ctx.pid;

			if (pid) {
				self.log('runScript: %s %s (pid #%d)', script, args.join(' '), pid);
			} else {
				done();
			}
		});
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.setMarkerMetric"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMarkerMetric (name)](#apidoc.element.phantomas.phantomas.prototype.setMarkerMetric)
- description and source-code
```javascript
setMarkerMetric = function (name) {
		var now = Date.now(),
			value = now - this.responseEndTime;

		if (typeof this.responseEndTime === 'undefined') {
			throw 'setMarkerMetric() called before responseEnd event!';
		}

		this.setMetric(name, value, true /* isFinal */ );
		return value;
	}
```
- example usage
```shell
...
				break;

			case 'addToAvgMetric':
				this.addToAvgMetric(data.name, data.value);
				break;

			case 'setMarkerMetric':
				this.setMarkerMetric(data.name);
				break;

			case 'addOffender':
				this.addOffender.apply(this, data);
				break;

			case 'emit':
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.setMetric"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMetric (name, value, isFinal)](#apidoc.element.phantomas.phantomas.prototype.setMetric)
- description and source-code
```javascript
setMetric = function (name, value, isFinal) {
		value = typeof value === 'string' ? value : (value || 0); // set to zero if undefined / null is provided
		this.results.setMetric(name, value);

		// trigger an event when the metric value is said to be final (isse #240)
		if (isFinal === true) {
			this.emit('metric', name, value); // @desc the metric is given the final value
		}
	}
```
- example usage
```shell
...
				// add debug info about pending responses (issue #216)
				self.on('timeout', function() {
					var timedOutRequests = Object.keys(requestsUrls);

					self.log('Timeout: gave up waiting for %d HTTP response(s): <%s>', currentRequests, timedOutRequests.join('>, <'));

					// emit timed out requests as a fake metric (#539)
					self.results.setMetric('requestsWithTimeout', timedOutRequests.length);

					timedOutRequests.forEach(function(url) {
						self.results.addOffender('requestsWithTimeout', url);
					});
				});

				// always register the metric (issue #581)
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.setMetricEvaluate"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>setMetricEvaluate (name, fn)](#apidoc.element.phantomas.phantomas.prototype.setMetricEvaluate)
- description and source-code
```javascript
setMetricEvaluate = function (name, fn) {
		this.setMetric(name, this.page.evaluate(fn), true /* isFinal */ );
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.tearDown"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>tearDown (exitCode, msg)](#apidoc.element.phantomas.phantomas.prototype.tearDown)
- description and source-code
```javascript
tearDown = function (exitCode, msg) {
		exitCode = exitCode || EXIT_SUCCESS;

		if (exitCode > 0) {
			this.log('Exiting with code #%d%s!', exitCode, msg ? ' (' + msg + ')' : '');
		}

		this.emit('exit', exitCode, msg);
		this.page.close();

		phantom.exit(exitCode);
	}
```
- example usage
```shell
...

		// emit results in JSON
		var formatter = require('./formatter');
		this.emit('json', formatter(this.results));

		// handle timeouts (issue #129)
		if (this.timedOut) {
			this.tearDown(EXIT_TIMED_OUT, 'Timeout');
			return;
		}

		// asserts handling
		var failedAsserts = this.results.getFailedAsserts(),
			failedAssertsCnt = failedAsserts.length;
...
```

#### <a name="apidoc.element.phantomas.phantomas.prototype.tmpdir"></a>[function <span class="apidocSignatureSpan">phantomas.phantomas.prototype.</span>tmpdir ()](#apidoc.element.phantomas.phantomas.prototype.tmpdir)
- description and source-code
```javascript
tmpdir = function () {
		// example: /tmp/phantomas/58aea8b5-2c97-48ee-9885-fcd81d38561f/
		return require('system').env.PHANTOMAS_TMP_DIR;
	}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.stats"></a>[module phantomas.stats](#apidoc.module.phantomas.stats)

#### <a name="apidoc.element.phantomas.stats.stats"></a>[function <span class="apidocSignatureSpan">phantomas.</span>stats ()](#apidoc.element.phantomas.stats.stats)
- description and source-code
```javascript
function stats() {
	<span class="apidocCodeCommentSpan">/* jshint validthis: true */
</span>	// use pushMetrics() to add results for each run
	this.metrics = [];
	this.runs = 0;

	// stats to be calculated
	// @see https://github.com/bluesmoon/node-faststats
	this.stats = {
		min: function(values) {
			return values.range()[0];
		},
		max: function(values) {
			return values.range()[1];
		},
		average: function(values) {
			return values.amean().toFixed(2);
		},
		median: function(values) {
			return values.median().toFixed(2);
		},
		stddev: function(values) {
			return values.stddev().toFixed(2);
		}
	};

	this.statsNames = Object.keys(this.stats);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.phantomas.stats.prototype"></a>[module phantomas.stats.prototype](#apidoc.module.phantomas.stats.prototype)

#### <a name="apidoc.element.phantomas.stats.prototype.getAvailableStats"></a>[function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getAvailableStats ()](#apidoc.element.phantomas.stats.prototype.getAvailableStats)
- description and source-code
```javascript
getAvailableStats = function () {
	return this.statsNames;
}
```
- example usage
```shell
...

		if (typeof value === 'number') {
			values.push(this.metrics[i][metricName]);
		}
	}

	// apply stats functions
	this.getAvailableStats().forEach(function(fnName) {
		stats[fnName] = parseFloat(this.stats[fnName](values));
	}, this);

	return stats;
};

stats.prototype.getAvailableStats = function() {
...
```

#### <a name="apidoc.element.phantomas.stats.prototype.getMetricStats"></a>[function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getMetricStats (metricName)](#apidoc.element.phantomas.stats.prototype.getMetricStats)
- description and source-code
```javascript
getMetricStats = function (metricName) {
	var i,
		stats = {},
		value,
		values = new Stats();

	for (i = 0; i < this.runs; i++) {
		value = this.metrics[i][metricName];

		if (typeof value === 'number') {
			values.push(this.metrics[i][metricName]);
		}
	}

	// apply stats functions
	this.getAvailableStats().forEach(function(fnName) {
		stats[fnName] = parseFloat(this.stats[fnName](values));
	}, this);

	return stats;
}
```
- example usage
```shell
...

				// generate metrics stats (issue #285)
				for (var i = 0, runs = results.length; i < runs; i++) {
					stats.pushMetrics(results[i].getMetrics());
				}

				stats.getMetrics().forEach(function(metricName) {
					res.stats[metricName] = stats.getMetricStats(metricName);
				});
			}

			// -R json:pretty
			if (reporterOptions.pretty === true) {
				return JSON.stringify(res, null, 2);
			} else {
...
```

#### <a name="apidoc.element.phantomas.stats.prototype.getMetrics"></a>[function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>getMetrics ()](#apidoc.element.phantomas.stats.prototype.getMetrics)
- description and source-code
```javascript
getMetrics = function () {
	if (this.runs > 0) {
		return Object.keys(this.metrics[0]);
	} else {
		return [];
	}
}
```
- example usage
```shell
...
 */
'use strict';

module.exports = function(results) {
	var res = {
		generator: results.getGenerator(),
		url: results.getUrl(),
		metrics: results.getMetrics(),
		offenders: results.getAllOffenders(),
		asserts: false
	};

	// add asserts
	var asserts = results.getAsserts();
...
```

#### <a name="apidoc.element.phantomas.stats.prototype.pushMetrics"></a>[function <span class="apidocSignatureSpan">phantomas.stats.prototype.</span>pushMetrics (metrics)](#apidoc.element.phantomas.stats.prototype.pushMetrics)
- description and source-code
```javascript
pushMetrics = function (metrics) {
	this.metrics.push(metrics);
	this.runs++;
}
```
- example usage
```shell
...
						return formatSingleRunResults(run);
					}),
					stats: {}
				};

				// generate metrics stats (issue #285)
				for (var i = 0, runs = results.length; i < runs; i++) {
					stats.pushMetrics(results[i].getMetrics());
				}

				stats.getMetrics().forEach(function(metricName) {
					res.stats[metricName] = stats.getMetricStats(metricName);
				});
			}
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
