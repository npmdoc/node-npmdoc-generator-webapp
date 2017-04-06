# api documentation for  [generator-webapp (v2.4.1)](https://github.com/yeoman/generator-webapp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-webapp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-webapp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-webapp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-webapp)
#### Scaffold out a front-end web app

[![NPM](https://nodei.co/npm/generator-webapp.png?downloads=true)](https://www.npmjs.com/package/generator-webapp)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-webapp/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-generator-webapp_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-webapp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-webapp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-webapp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "The Yeoman Team"
    },
    "bugs": {
        "url": "https://github.com/yeoman/generator-webapp/issues"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "generator-jasmine": "^0.2.1",
        "generator-mocha": "^0.3.1",
        "mkdirp": "^0.5.1",
        "underscore.string": "^3.1.1",
        "wiredep": "^4.0.0",
        "yeoman-assert": "^2.1.1",
        "yeoman-generator": "^0.24.1",
        "yosay": "^1.2.0"
    },
    "description": "Scaffold out a front-end web app",
    "devDependencies": {
        "mocha": "^3.1.0",
        "yeoman-test": "^1.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6856635234a2f2622fef32c1fa0c1eef766c1b73",
        "tarball": "https://registry.npmjs.org/generator-webapp/-/generator-webapp-2.4.1.tgz"
    },
    "engines": {
        "node": ">=4",
        "npm": ">=1.3"
    },
    "files": [
        "app"
    ],
    "gitHead": "f86304a643dccc0398101eead43476096274c98e",
    "homepage": "https://github.com/yeoman/generator-webapp#readme",
    "keywords": [
        "yeoman-generator",
        "web",
        "app",
        "front-end",
        "h5bp",
        "modernizr",
        "jquery",
        "gulp"
    ],
    "license": "BSD-2-Clause",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "eddiemonge",
            "email": "eddie+npm@eddiemonge.com"
        },
        {
            "name": "paulirish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "sboudrias",
            "email": "admin@simonboudrias.com"
        },
        {
            "name": "passy",
            "email": "phartig@rdrei.net"
        },
        {
            "name": "addyosmani",
            "email": "addyosmani@gmail.com"
        },
        {
            "name": "silvenon",
            "email": "matija.marohnic@gmail.com"
        },
        {
            "name": "arthurvr",
            "email": "contact@arthurverschaeve.be"
        }
    ],
    "name": "generator-webapp",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/generator-webapp.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --timeout 3000"
    },
    "version": "2.4.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module generator-webapp](#apidoc.module.generator-webapp)
1.  [function <span class="apidocSignatureSpan">generator-webapp.</span>extend (protoProps, staticProps)](#apidoc.element.generator-webapp.extend)
1.  [function <span class="apidocSignatureSpan">generator-webapp.</span>super_ ()](#apidoc.element.generator-webapp.super_)
1.  object <span class="apidocSignatureSpan">generator-webapp.</span>__super__

#### [module generator-webapp.__super__](#apidoc.module.generator-webapp.__super__)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_directory (source, destination, process, bulk)](#apidoc.element.generator-webapp.__super__._directory)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_getGlobalStorage ()](#apidoc.element.generator-webapp.__super__._getGlobalStorage)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_getStorage ()](#apidoc.element.generator-webapp.__super__._getStorage)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_writeFiles (done)](#apidoc.element.generator-webapp.__super__._writeFiles)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>append ()](#apidoc.element.generator-webapp.__super__.append)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendFiles ()](#apidoc.element.generator-webapp.__super__.appendFiles)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendIndent ()](#apidoc.element.generator-webapp.__super__.appendIndent)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendScripts ()](#apidoc.element.generator-webapp.__super__.appendScripts)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendScriptsDir ()](#apidoc.element.generator-webapp.__super__.appendScriptsDir)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendStyles ()](#apidoc.element.generator-webapp.__super__.appendStyles)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendStylesDir ()](#apidoc.element.generator-webapp.__super__.appendStylesDir)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendToFile ()](#apidoc.element.generator-webapp.__super__.appendToFile)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>argument (name, config)](#apidoc.element.generator-webapp.__super__.argument)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>argumentsHelp ()](#apidoc.element.generator-webapp.__super__.argumentsHelp)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>attributes ()](#apidoc.element.generator-webapp.__super__.attributes)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bowerInstall (cmpnt, options, cb)](#apidoc.element.generator-webapp.__super__.bowerInstall)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bulkCopy (source, dest)](#apidoc.element.generator-webapp.__super__.bulkCopy)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bulkDirectory (source, destination, process)](#apidoc.element.generator-webapp.__super__.bulkDirectory)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>checkRequiredArgs ()](#apidoc.element.generator-webapp.__super__.checkRequiredArgs)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>composeWith (namespace, options, settings)](#apidoc.element.generator-webapp.__super__.composeWith)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>copy (source, dest)](#apidoc.element.generator-webapp.__super__.copy)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>defaultFor (name)](#apidoc.element.generator-webapp.__super__.defaultFor)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>desc (description)](#apidoc.element.generator-webapp.__super__.desc)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>destinationPath ()](#apidoc.element.generator-webapp.__super__.destinationPath)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>destinationRoot (rootPath)](#apidoc.element.generator-webapp.__super__.destinationRoot)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>determineAppname ()](#apidoc.element.generator-webapp.__super__.determineAppname)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>directory (source, destination, process)](#apidoc.element.generator-webapp.__super__.directory)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>domUpdate ()](#apidoc.element.generator-webapp.__super__.domUpdate)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>expand ()](#apidoc.element.generator-webapp.__super__.expand)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>expandFiles ()](#apidoc.element.generator-webapp.__super__.expandFiles)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>extract ()](#apidoc.element.generator-webapp.__super__.extract)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>fetch ()](#apidoc.element.generator-webapp.__super__.fetch)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>generateBlock ()](#apidoc.element.generator-webapp.__super__.generateBlock)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>help ()](#apidoc.element.generator-webapp.__super__.help)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>hookFor ()](#apidoc.element.generator-webapp.__super__.hookFor)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>installDependencies (options)](#apidoc.element.generator-webapp.__super__.installDependencies)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>invoke ()](#apidoc.element.generator-webapp.__super__.invoke)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>isPathAbsolute ()](#apidoc.element.generator-webapp.__super__.isPathAbsolute)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>mkdir ()](#apidoc.element.generator-webapp.__super__.mkdir)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>npmInstall (pkgs, options, cb)](#apidoc.element.generator-webapp.__super__.npmInstall)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>option (name, config)](#apidoc.element.generator-webapp.__super__.option)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>optionsHelp ()](#apidoc.element.generator-webapp.__super__.optionsHelp)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>parseOptions ()](#apidoc.element.generator-webapp.__super__.parseOptions)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prepend ()](#apidoc.element.generator-webapp.__super__.prepend)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prependToFile ()](#apidoc.element.generator-webapp.__super__.prependToFile)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prompt (questions)](#apidoc.element.generator-webapp.__super__.prompt)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>read (filepath, encoding)](#apidoc.element.generator-webapp.__super__.read)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>readFileAsString ()](#apidoc.element.generator-webapp.__super__.readFileAsString)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>registerTransformStream (streams)](#apidoc.element.generator-webapp.__super__.registerTransformStream)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>remote ()](#apidoc.element.generator-webapp.__super__.remote)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>remoteDir ()](#apidoc.element.generator-webapp.__super__.remoteDir)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>removeScript ()](#apidoc.element.generator-webapp.__super__.removeScript)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>removeStyle ()](#apidoc.element.generator-webapp.__super__.removeStyle)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>rootGeneratorName ()](#apidoc.element.generator-webapp.__super__.rootGeneratorName)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>rootGeneratorVersion ()](#apidoc.element.generator-webapp.__super__.rootGeneratorVersion)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>run (cb)](#apidoc.element.generator-webapp.__super__.run)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>runHooks (cb)](#apidoc.element.generator-webapp.__super__.runHooks)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>runInstall (installer, paths, options, cb)](#apidoc.element.generator-webapp.__super__.runInstall)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>sourceRoot (rootPath)](#apidoc.element.generator-webapp.__super__.sourceRoot)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>spawnCommand (command, args, opt)](#apidoc.element.generator-webapp.__super__.spawnCommand)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>spawnCommandSync (command, args, opt)](#apidoc.element.generator-webapp.__super__.spawnCommandSync)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>tarball ()](#apidoc.element.generator-webapp.__super__.tarball)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>template (source, dest, data, options)](#apidoc.element.generator-webapp.__super__.template)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>templatePath ()](#apidoc.element.generator-webapp.__super__.templatePath)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>usage ()](#apidoc.element.generator-webapp.__super__.usage)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>welcome ()](#apidoc.element.generator-webapp.__super__.welcome)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>write (filepath, content)](#apidoc.element.generator-webapp.__super__.write)
1.  [function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>writeFileFromString ()](#apidoc.element.generator-webapp.__super__.writeFileFromString)
1.  object <span class="apidocSignatureSpan">generator-webapp.__super__.</span>defaults
1.  object <span class="apidocSignatureSpan">generator-webapp.__super__.</span>user



# <a name="apidoc.module.generator-webapp"></a>[module generator-webapp](#apidoc.module.generator-webapp)

#### <a name="apidoc.element.generator-webapp.extend"></a>[function <span class="apidocSignatureSpan">generator-webapp.</span>extend (protoProps, staticProps)](#apidoc.element.generator-webapp.extend)
- description and source-code
```javascript
function extend(protoProps, staticProps) {
  var parent = this;
  var child;

  // The constructor function for the new subclass is either defined by you
  // (the "constructor" property in your 'extend' definition), or defaulted
  // by us to simply call the parent's constructor.
  if (protoProps && hasOwnProp.call(protoProps, 'constructor')) {
    child = protoProps.constructor;
  } else {
    child = function () { return parent.apply(this, arguments); };
  }

  // Add static properties to the constructor function, if supplied.
  objectAssign(child, parent, staticProps);

  // Set the prototype chain to inherit from 'parent'
  child.prototype = Object.create(parent.prototype, {
    constructor: {
      value: child,
      enumerable: false,
      writable: true,
      configurable: true
    }
  });

  // Add prototype properties (instance properties) to the subclass,
  // if supplied.
  if (protoProps) objectAssign(child.prototype, protoProps);

  // Set a convenience property in case the parent's prototype is needed
  // later.
  child.__super__ = parent.prototype;

  return child;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.super_"></a>[function <span class="apidocSignatureSpan">generator-webapp.</span>super_ ()](#apidoc.element.generator-webapp.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-webapp.__super__"></a>[module generator-webapp.__super__](#apidoc.module.generator-webapp.__super__)

#### <a name="apidoc.element.generator-webapp.__super__._directory"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_directory (source, destination, process, bulk)](#apidoc.element.generator-webapp.__super__._directory)
- description and source-code
```javascript
function _directory(source, destination, process, bulk) {
  // Only add sourceRoot if the path is not absolute
  var root = this.templatePath(source);
  var files = glob.sync('**', { dot: true, nodir: true, cwd: root });

  destination = destination || source;

  if (typeof destination === 'function') {
    process = destination;
    destination = source;
  }

  var cp = this.copy;

  if (bulk) {
    cp = this.bulkCopy;
  }

  // get the path relative to the template root, and copy to the relative destination
  for (var i in files) {
    var dest = path.join(destination, files[i]);
    cp.call(this, path.join(root, files[i]), dest, process);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__._getGlobalStorage"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_getGlobalStorage ()](#apidoc.element.generator-webapp.__super__._getGlobalStorage)
- description and source-code
```javascript
_getGlobalStorage = function () {
  var storePath = path.join(userHome, '.yo-rc-global.json');
  var storeName = util.format('%s:%s', this.rootGeneratorName(), this.rootGeneratorVersion());
  return new Storage(storeName, this.fs, storePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__._getStorage"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_getStorage ()](#apidoc.element.generator-webapp.__super__._getStorage)
- description and source-code
```javascript
_getStorage = function () {
  var storePath = path.join(this.destinationRoot(), '.yo-rc.json');
  return new Storage(this.rootGeneratorName(), this.fs, storePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__._writeFiles"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>_writeFiles (done)](#apidoc.element.generator-webapp.__super__._writeFiles)
- description and source-code
```javascript
_writeFiles = function (done) {
  var self = this;

  var conflictChecker = through.obj(function (file, enc, cb) {
    var stream = this;

    // If the file has no state requiring action, move on
    if (file.state === null) {
      return cb();
    }

    // Config file should not be processed by the conflicter. Just pass through
    var filename = path.basename(file.path);

    if (filename === '.yo-rc.json' || filename === '.yo-rc-global.json') {
      this.push(file);
      return cb();
    }

    self.conflicter.checkForCollision(file.path, file.contents, function (err, status) {
      if (err) {
        cb(err);
        return;
      }

      if (status === 'skip') {
        delete file.state;
      } else {
        stream.push(file);
      }

      cb();
    });
    self.conflicter.resolve();
  });

  var transformStreams = this._transformStreams.concat([conflictChecker]);
  this.fs.commit(transformStreams, function () {
    done();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.append"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>append ()](#apidoc.element.generator-webapp.__super__.append)
- description and source-code
```javascript
append = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendFiles"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendFiles ()](#apidoc.element.generator-webapp.__super__.appendFiles)
- description and source-code
```javascript
appendFiles = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendIndent"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendIndent ()](#apidoc.element.generator-webapp.__super__.appendIndent)
- description and source-code
```javascript
appendIndent = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendScripts"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendScripts ()](#apidoc.element.generator-webapp.__super__.appendScripts)
- description and source-code
```javascript
appendScripts = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendScriptsDir"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendScriptsDir ()](#apidoc.element.generator-webapp.__super__.appendScriptsDir)
- description and source-code
```javascript
appendScriptsDir = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendStyles"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendStyles ()](#apidoc.element.generator-webapp.__super__.appendStyles)
- description and source-code
```javascript
appendStyles = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendStylesDir"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendStylesDir ()](#apidoc.element.generator-webapp.__super__.appendStylesDir)
- description and source-code
```javascript
appendStylesDir = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.appendToFile"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>appendToFile ()](#apidoc.element.generator-webapp.__super__.appendToFile)
- description and source-code
```javascript
appendToFile = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.argument"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>argument (name, config)](#apidoc.element.generator-webapp.__super__.argument)
- description and source-code
```javascript
function argument(name, config) {
  config = config || {};

  // alias default to defaults for backward compatibility.
  config.default = config.default || config.defaults;

  _.defaults(config, {
    name: name,
    required: config.default == null,
    type: String
  });


  var position = this._arguments.length;
  this._arguments.push({
    name: name,
    config: config
  });

  Object.defineProperty(this, name, {
    configurable: true,
    enumerable: true,
    get: function () {
      // a bit of coercion and type handling, to be improved
      // just dealing with Array/String, default is assumed to be String
      var value = config.type === Array ? this.args.slice(position) : this.args[position];
      return position >= this.args.length ? config.default : value;
    },
    set: function (value) {
      this.args[position] = value;
    }
  });

  this.checkRequiredArgs();
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.argumentsHelp"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>argumentsHelp ()](#apidoc.element.generator-webapp.__super__.argumentsHelp)
- description and source-code
```javascript
function argumentsHelp() {
  var rows = this._arguments.map(function (arg) {
    var config = arg.config;

    return [
      '',
      arg.name ? arg.name : '',
      config.desc ? '# ' + config.desc : '',
      config.type ? 'Type: ' + config.type.name : '',
      'Required: ' + config.required
    ];
  });

  return table(rows);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.attributes"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>attributes ()](#apidoc.element.generator-webapp.__super__.attributes)
- description and source-code
```javascript
attributes = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.bowerInstall"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bowerInstall (cmpnt, options, cb)](#apidoc.element.generator-webapp.__super__.bowerInstall)
- description and source-code
```javascript
function install(cmpnt, options, cb) {
  return this.runInstall('bower', cmpnt, options, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.bulkCopy"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bulkCopy (source, dest)](#apidoc.element.generator-webapp.__super__.bulkCopy)
- description and source-code
```javascript
function bulkCopy(source, dest) {
  source = this.templatePath(source);
  dest = this.destinationPath(dest);
  var body = fs.readFileSync(source);

  mkdirp.sync(path.dirname(dest));
  fs.writeFileSync(dest, body);

  // synchronize stats and modification times from the original file.
  var stats = fs.statSync(source);

  try {
    fs.chmodSync(dest, stats.mode);
    fs.utimesSync(dest, stats.atime, stats.mtime);
  } catch (err) {
    this.log.error('Error setting permissions of "' + chalk.bold(dest) + '" file: ' + err);
  }

  this.log.create(dest);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.bulkDirectory"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>bulkDirectory (source, destination, process)](#apidoc.element.generator-webapp.__super__.bulkDirectory)
- description and source-code
```javascript
function directory(source, destination, process) {
  // Join the source here because the conflicter will not run
  // until next tick, which resets the source root on remote
  // bulkCopy operations
  source = path.join(this.sourceRoot(), source);

  this.conflicter.checkForCollision(destination, null, function (err, status) {
    // create or force means file write, identical or skip prevent the
    // actual write.
    if (/force|create/.test(status)) {
      this._directory(source, destination, process, true);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.checkRequiredArgs"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>checkRequiredArgs ()](#apidoc.element.generator-webapp.__super__.checkRequiredArgs)
- description and source-code
```javascript
checkRequiredArgs = function () {
  // If the help option was provided, we don't want to check for required
  // arguments, since we're only going to print the help message anyway.
  if (this.options.help) {
    return;
  }

  // Bail early if it's not possible to have a missing required arg
  if (this.args.length > this._arguments.length) {
    return;
  }

  this._arguments.forEach(function (arg, position) {
    // If the help option was not provided, check whether the argument was
    // required, and whether a value was provided.
    if (arg.config.required && position >= this.args.length) {
      return this.emit('error', new Error('Did not provide required argument ' + chalk.bold(arg.name) + '!'));
    }
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.composeWith"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>composeWith (namespace, options, settings)](#apidoc.element.generator-webapp.__super__.composeWith)
- description and source-code
```javascript
function composeWith(namespace, options, settings) {
  settings = settings || {};
  var generator;

  if (settings.local) {
    var Generator = require(settings.local);
    Generator.resolved = require.resolve(settings.local);
    Generator.namespace = namespace;
    generator = this.env.instantiate(Generator, options);
  } else {
    generator = this.env.create(namespace, options);
  }

  if (this._running) {
    generator.run();
  } else {
    this._composedWith.push(generator);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.copy"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>copy (source, dest)](#apidoc.element.generator-webapp.__super__.copy)
- description and source-code
```javascript
function copy(source, dest) {
  dest = dest || source;
  source = this.templatePath(source);
  var headers = readChunk.sync(source, 0, 512);

  if (istextorbinary.isBinarySync(undefined, headers)) {
    this.fs.copy(source, this.destinationPath(dest));
  } else {
    this.template(source, dest);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.defaultFor"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>defaultFor (name)](#apidoc.element.generator-webapp.__super__.defaultFor)
- description and source-code
```javascript
function defaultFor(name) {
  return this.options[name] || name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.desc"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>desc (description)](#apidoc.element.generator-webapp.__super__.desc)
- description and source-code
```javascript
function desc(description) {
  this.description = description || '';
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.destinationPath"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>destinationPath ()](#apidoc.element.generator-webapp.__super__.destinationPath)
- description and source-code
```javascript
destinationPath = function () {
  var filepath = path.join.apply(path, arguments);

  if (!pathIsAbsolute(filepath)) {
    filepath = path.join(this.destinationRoot(), filepath);
  }

  return filepath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.destinationRoot"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>destinationRoot (rootPath)](#apidoc.element.generator-webapp.__super__.destinationRoot)
- description and source-code
```javascript
destinationRoot = function (rootPath) {
  if (_.isString(rootPath)) {
    this._destinationRoot = path.resolve(rootPath);

    if (!pathExists.sync(rootPath)) {
      mkdirp.sync(rootPath);
    }

    process.chdir(rootPath);
    this.env.cwd = rootPath;

    // Reset the storage
    this.config = this._getStorage();
  }

  return this._destinationRoot || this.env.cwd;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.determineAppname"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>determineAppname ()](#apidoc.element.generator-webapp.__super__.determineAppname)
- description and source-code
```javascript
determineAppname = function () {
  var appname = this.fs.readJSON(this.destinationPath('bower.json'), {}).name;

  if (!appname) {
    appname = this.fs.readJSON(this.destinationPath('package.json'), {}).name;
  }

  if (!appname) {
    appname = path.basename(this.destinationRoot());
  }

  return appname.replace(/[^\w\s]+?/g, ' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.directory"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>directory (source, destination, process)](#apidoc.element.generator-webapp.__super__.directory)
- description and source-code
```javascript
function directory(source, destination, process) {
  return this._directory(source, destination, process);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.domUpdate"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>domUpdate ()](#apidoc.element.generator-webapp.__super__.domUpdate)
- description and source-code
```javascript
domUpdate = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.expand"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>expand ()](#apidoc.element.generator-webapp.__super__.expand)
- description and source-code
```javascript
expand = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.expandFiles"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>expandFiles ()](#apidoc.element.generator-webapp.__super__.expandFiles)
- description and source-code
```javascript
expandFiles = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.extract"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>extract ()](#apidoc.element.generator-webapp.__super__.extract)
- description and source-code
```javascript
extract = function () {
  deprecate.log('Remotes functions are deprecated. See https://github.com/yeoman/generator/issues/949 for update guide.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.fetch"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>fetch ()](#apidoc.element.generator-webapp.__super__.fetch)
- description and source-code
```javascript
fetch = function () {
  deprecate.log('Remotes functions are deprecated. See https://github.com/yeoman/generator/issues/949 for update guide.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.generateBlock"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>generateBlock ()](#apidoc.element.generator-webapp.__super__.generateBlock)
- description and source-code
```javascript
generateBlock = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.help"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>help ()](#apidoc.element.generator-webapp.__super__.help)
- description and source-code
```javascript
function help() {
  var filepath = path.join(this.sourceRoot(), '../USAGE');
  var exists = pathExists.sync(filepath);
  var out = [
    'Usage:',
    '  ' + this.usage(),
    ''
  ];

  // build options
  if (Object.keys(this._options).length) {
    out = out.concat([
      'Options:',
      this.optionsHelp(),
      ''
    ]);
  }

  // build arguments
  if (this._arguments.length) {
    out = out.concat([
      'Arguments:',
      this.argumentsHelp(),
      ''
    ]);
  }

  // append USAGE file is any
  if (exists) {
    out.push(fs.readFileSync(filepath, 'utf8'));
  }

  return out.join('\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.hookFor"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>hookFor ()](#apidoc.element.generator-webapp.__super__.hookFor)
- description and source-code
```javascript
hookFor = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.installDependencies"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>installDependencies (options)](#apidoc.element.generator-webapp.__super__.installDependencies)
- description and source-code
```javascript
installDependencies = function (options) {
  var commands = [];
  var msg = {
    commands: [],
    template: _.template('\n\nI\'m all done. ' +
    '<%= skipInstall ? "Just run" : "Running" %> <%= commands %> ' +
    '<%= skipInstall ? "" : "for you " %>to install the required dependencies.' +
    '<% if (!skipInstall) { %> If this fails, try running the command yourself.<% } %>\n\n')
  };

  if (_.isFunction(options)) {
    options = {
      callback: options
    };
  }

  options = _.defaults(options || {}, {
    bower: true,
    npm: true,
    skipMessage: false,
    callback: function () {}
  });

  if (options.npm) {
    msg.commands.push('npm install');
    commands.push(function (cb) {
      this.npmInstall(null, null, cb);
    }.bind(this));
  }

  if (options.bower) {
    msg.commands.push('bower install');
    commands.push(function (cb) {
      this.bowerInstall(null, null, cb);
    }.bind(this));
  }

  assert(msg.commands.length, 'installDependencies needs at least one of 'npm' or 'bower' to run.');

  if (!options.skipMessage) {
    var tplValues = _.extend({
      skipInstall: false
    }, this.options, {
      commands: chalk.yellow.bold(msg.commands.join(' && '))
    });
    this.log(msg.template(tplValues));
  }

  async.parallel(commands, options.callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.invoke"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>invoke ()](#apidoc.element.generator-webapp.__super__.invoke)
- description and source-code
```javascript
invoke = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.isPathAbsolute"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>isPathAbsolute ()](#apidoc.element.generator-webapp.__super__.isPathAbsolute)
- description and source-code
```javascript
isPathAbsolute = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.mkdir"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>mkdir ()](#apidoc.element.generator-webapp.__super__.mkdir)
- description and source-code
```javascript
mkdir = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.npmInstall"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>npmInstall (pkgs, options, cb)](#apidoc.element.generator-webapp.__super__.npmInstall)
- description and source-code
```javascript
function install(pkgs, options, cb) {
  return this.runInstall('npm', pkgs, options, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.option"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>option (name, config)](#apidoc.element.generator-webapp.__super__.option)
- description and source-code
```javascript
function option(name, config) {
  config = config || {};
  _.defaults(config, {
    name: name,
    desc: 'Description for ' + name,
    type: Boolean,
    default: config.defaults,
    hide: false
  });

  if (this._options[name] == null) {
    this._options[name] = config;
  }

  if (this.options[name] == null && config.alias) {
    this.options[name] = this.options[config.alias];
  }

  if (this.options[name] == null) {
    this.options[name] = config.default;
  }

  this.parseOptions();
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.optionsHelp"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>optionsHelp ()](#apidoc.element.generator-webapp.__super__.optionsHelp)
- description and source-code
```javascript
function optionsHelp() {
  var options = _.reject(this._options, function (el) {
    return el.hide;
  });

  var hookOpts = this._hooks.map(function (hook) {
    return hook.generator && hook.generator._options;
  }).reduce(function (a, b) {
    a = a.concat(b);
    return a;
  }, []).filter(function (opts) {
    return opts && opts.name !== 'help';
  });

  var rows = options.concat(hookOpts).map(function (opt) {
    var defaults = opt.default;

    return [
      '',
      opt.alias ? '-' + opt.alias + ', ' : '',
      '--' + opt.name,
      opt.desc ? '# ' + opt.desc : '',
      defaults == null || defaults === '' ? '' : 'Default: ' + defaults
    ];
  });

  return table(rows);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.parseOptions"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>parseOptions ()](#apidoc.element.generator-webapp.__super__.parseOptions)
- description and source-code
```javascript
parseOptions = function () {
  var opts = {};
  var shortOpts = {};

  _.each(this._options, function (option) {
    opts[option.name] = option.type;

    if (option.alias) {
      shortOpts[option.alias] = '--' + option.name;
    }
  });

  opts = nopt(opts, shortOpts, this._args, 0);
  _.extend(this.options, opts);

  this.args = this.arguments = opts.argv.remain;
  this.checkRequiredArgs();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.prepend"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prepend ()](#apidoc.element.generator-webapp.__super__.prepend)
- description and source-code
```javascript
prepend = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.prependToFile"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prependToFile ()](#apidoc.element.generator-webapp.__super__.prependToFile)
- description and source-code
```javascript
prependToFile = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.prompt"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>prompt (questions)](#apidoc.element.generator-webapp.__super__.prompt)
- description and source-code
```javascript
prompt = function (questions) {
  questions = promptSuggestion.prefillQuestions(this._globalConfig, questions);

  return this.env.adapter.prompt(questions).then(function (answers) {
    if (!this.options['skip-cache']) {
      promptSuggestion.storeAnswers(this._globalConfig, questions, answers);
    }

    return answers;
  }.bind(this));

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.read"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>read (filepath, encoding)](#apidoc.element.generator-webapp.__super__.read)
- description and source-code
```javascript
function read(filepath, encoding) {
  var contents = this.fs.read(this.templatePath(filepath), { raw: true });
  return contents.toString(encoding || 'utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.readFileAsString"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>readFileAsString ()](#apidoc.element.generator-webapp.__super__.readFileAsString)
- description and source-code
```javascript
readFileAsString = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.registerTransformStream"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>registerTransformStream (streams)](#apidoc.element.generator-webapp.__super__.registerTransformStream)
- description and source-code
```javascript
registerTransformStream = function (streams) {
  assert(streams, 'expected to receive a transform stream as parameter');
  if (!_.isArray(streams)) {
    streams = [streams];
  }
  this._transformStreams = this._transformStreams.concat(streams);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.remote"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>remote ()](#apidoc.element.generator-webapp.__super__.remote)
- description and source-code
```javascript
remote = function () {
  deprecate.log('Remotes functions are deprecated. See https://github.com/yeoman/generator/issues/949 for update guide.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.remoteDir"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>remoteDir ()](#apidoc.element.generator-webapp.__super__.remoteDir)
- description and source-code
```javascript
remoteDir = function () {
  deprecate.log('Remotes functions are deprecated. See https://github.com/yeoman/generator/issues/949 for update guide.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.removeScript"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>removeScript ()](#apidoc.element.generator-webapp.__super__.removeScript)
- description and source-code
```javascript
removeScript = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.removeStyle"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>removeStyle ()](#apidoc.element.generator-webapp.__super__.removeStyle)
- description and source-code
```javascript
removeStyle = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.rootGeneratorName"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>rootGeneratorName ()](#apidoc.element.generator-webapp.__super__.rootGeneratorName)
- description and source-code
```javascript
rootGeneratorName = function () {
  var pkg = readPkgUp.sync({cwd: this.resolved}).pkg;
  return pkg ? pkg.name : '*';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.rootGeneratorVersion"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>rootGeneratorVersion ()](#apidoc.element.generator-webapp.__super__.rootGeneratorVersion)
- description and source-code
```javascript
rootGeneratorVersion = function () {
  var pkg = readPkgUp.sync({cwd: this.resolved}).pkg;
  return pkg ? pkg.version : '0.0.0';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.run"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>run (cb)](#apidoc.element.generator-webapp.__super__.run)
- description and source-code
```javascript
function run(cb) {
  cb = cb || function () {};

  var self = this;
  this._running = true;
  this.emit('run');

  var methods = Object.getOwnPropertyNames(Object.getPrototypeOf(this));
  var validMethods = methods.filter(methodIsValid);
  assert(validMethods.length, 'This Generator is empty. Add at least one method for it to run.');

  this.env.runLoop.once('end', function () {
    this.emit('end');
    cb();
  }.bind(this));

  // Ensure a prototype method is a candidate run by default
  function methodIsValid(name) {
    return name.charAt(0) !== '_' && name !== 'constructor';
  }

  function addMethod(method, methodName, queueName) {
    queueName = queueName || 'default';
    debug('Queueing ' + methodName + ' in ' + queueName);
    self.env.runLoop.add(queueName, function (completed) {
      debug('Running ' + methodName);
      self.emit('method:' + methodName);

      runAsync(function () {
        self.async = function () {
          return this.async();
        }.bind(this);

        return method.apply(self, self.args);
      })().then(completed).catch(function (err) {
        debug('An error occured while running ' + methodName, err);

        // Ensure we emit the error event outside the promise context so it won't be
        // swallowed when there's no listeners.
        setImmediate(function () {
          self.emit('error', err);
          cb(err);
        });
      });
    });
  }

  function addInQueue(name) {
    var item = Object.getPrototypeOf(self)[name];
    var queueName = self.env.runLoop.queueNames.indexOf(name) !== -1 ? name : null;

    // Name points to a function; run it!
    if (_.isFunction(item)) {
      return addMethod(item, name, queueName);
    }

    // Not a queue hash; stop
    if (!queueName) {
      return;
    }

    // Run each queue items
    _.each(item, function (method, methodName) {
      if (!_.isFunction(method) || !methodIsValid(methodName)) {
        return;
      }

      addMethod(method, methodName, queueName);
    });
  }

  validMethods.forEach(addInQueue);

  var writeFiles = function () {
    this.env.runLoop.add('conflicts', this._writeFiles.bind(this), {
      once: 'write memory fs to disk'
    });
  }.bind(this);

  this.env.sharedFs.on('change', writeFiles);
  writeFiles();

  // Add the default conflicts handling
  this.env.runLoop.add('conflicts', function (done) {
    this.conflicter.resolve(function (err) {
      if (err) {
        this.emit('error', err);
      }

      done();
    }.bind(this));
  }.bind(this));

  this.on('end', function () {
    debug('Running the hooked generators');
    this.runHooks();
  });

  _.invokeMap(this._composedWith, 'run');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.runHooks"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>runHooks (cb)](#apidoc.element.generator-webapp.__super__.runHooks)
- description and source-code
```javascript
function runHooks(cb) {
  cb = _.isFunction(cb) ? cb : function () {};

  var setupInvoke = function (hook) {
    var resolved = this.defaultFor(hook.name);
    var options = _.clone(hook.options || this.options);
    options.args = _.clone(hook.args || this.args);

    return function (next) {
      this.invoke(resolved + (hook.as ? ':' + hook.as : ''), options, next);
    }.bind(this);
  }.bind(this);

  async.series(this._hooks.map(setupInvoke), cb);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.runInstall"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>runInstall (installer, paths, options, cb)](#apidoc.element.generator-webapp.__super__.runInstall)
- description and source-code
```javascript
runInstall = function (installer, paths, options, cb) {
  if (!cb && _.isFunction(options)) {
    cb = options;
    options = {};
  }

  options = options || {};
  cb = cb || function () {};
  paths = Array.isArray(paths) ? paths : paths && paths.split(' ') || [];

  var args = ['install'].concat(paths).concat(dargs(options));

  // Return early if we're skipping installation.
  if (this.options.skipInstall) {
    cb();
    return this;
  }

  this.env.runLoop.add('install', function (done) {
    this.emit(installer + 'Install', paths);
    this.spawnCommand(installer, args, options)
      .on('error', cb)
      .on('exit', function (err) {
        if (err === 127) {
          this.log.error(
            'Could not find ' + installer + '. Please install with ' +
            ''npm install -g ' + installer + ''.'
          );
        }

        this.emit(installer + 'Install:end', paths);
        cb(err);
        done();
      }.bind(this));
  }.bind(this), { once: installer + ' ' + args.join(' '), run: false });

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.sourceRoot"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>sourceRoot (rootPath)](#apidoc.element.generator-webapp.__super__.sourceRoot)
- description and source-code
```javascript
sourceRoot = function (rootPath) {
  if (_.isString(rootPath)) {
    this._sourceRoot = path.resolve(rootPath);
  }

  return this._sourceRoot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.spawnCommand"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>spawnCommand (command, args, opt)](#apidoc.element.generator-webapp.__super__.spawnCommand)
- description and source-code
```javascript
function spawnCommand(command, args, opt) {
  opt = opt || {};
  return spawn(command, args, _.defaults(opt, { stdio: 'inherit' }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.spawnCommandSync"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>spawnCommandSync (command, args, opt)](#apidoc.element.generator-webapp.__super__.spawnCommandSync)
- description and source-code
```javascript
function spawnCommandSync(command, args, opt) {
  opt = opt || {};
  return spawn.sync(command, args, _.defaults(opt, { stdio: 'inherit' }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.tarball"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>tarball ()](#apidoc.element.generator-webapp.__super__.tarball)
- description and source-code
```javascript
tarball = function () {
  deprecate.log('Remotes functions are deprecated. See https://github.com/yeoman/generator/issues/949 for update guide.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.template"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>template (source, dest, data, options)](#apidoc.element.generator-webapp.__super__.template)
- description and source-code
```javascript
function template(source, dest, data, options) {
  if (typeof dest !== 'string') {
    options = data;
    data = dest;
    dest = source;
  }

  this.fs.copyTpl(
    this.templatePath(source),
    this.destinationPath(dest),
    data || this,
    options
  );
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.templatePath"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>templatePath ()](#apidoc.element.generator-webapp.__super__.templatePath)
- description and source-code
```javascript
templatePath = function () {
  var filepath = path.join.apply(path, arguments);

  if (!pathIsAbsolute(filepath)) {
    filepath = path.join(this.sourceRoot(), filepath);
  }

  return filepath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.usage"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>usage ()](#apidoc.element.generator-webapp.__super__.usage)
- description and source-code
```javascript
function usage() {
  var options = Object.keys(this._options).length ? '[options]' : '';
  var name = ' ' + this.options.namespace;
  var args = '';

  if (this._arguments.length) {
    args = this._arguments.map(formatArg).join(' ');
  }

  name = name.replace(/^yeoman:/, '');
  var out = 'yo' + name + ' ' + options + ' ' + args;

  if (this.description) {
    out += '\n\n' + this.description;
  }

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.welcome"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>welcome ()](#apidoc.element.generator-webapp.__super__.welcome)
- description and source-code
```javascript
welcome = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.write"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>write (filepath, content)](#apidoc.element.generator-webapp.__super__.write)
- description and source-code
```javascript
function write(filepath, content) {
  this.fs.write(this.destinationPath(filepath), content);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-webapp.__super__.writeFileFromString"></a>[function <span class="apidocSignatureSpan">generator-webapp.__super__.</span>writeFileFromString ()](#apidoc.element.generator-webapp.__super__.writeFileFromString)
- description and source-code
```javascript
writeFileFromString = function () {
  deprecate.log(message);
  return fn.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
