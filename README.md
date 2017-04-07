# api documentation for  [javascripting (v2.6.1)](https://github.com/sethvincent/javascripting#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-javascripting.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-javascripting) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-javascripting.svg)](https://travis-ci.org/npmdoc/node-npmdoc-javascripting)
#### Learn JavaScript by adventuring around in the terminal.

[![NPM](https://nodei.co/npm/javascripting.png?downloads=true)](https://www.npmjs.com/package/javascripting)

[![apidoc](https://npmdoc.github.io/node-npmdoc-javascripting/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-javascripting_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-javascripting/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-javascripting/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-javascripting/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sethvincent"
    },
    "bin": {
        "javascripting": "./bin/javascripting"
    },
    "bugs": {
        "url": "https://github.com/sethvincent/javascripting/issues"
    },
    "dependencies": {
        "colors": "^1.0.3",
        "diff": "^1.2.1",
        "promise": "^7.1.1",
        "workshopper-adventure": "^5.0.0"
    },
    "description": "Learn JavaScript by adventuring around in the terminal.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "bdfd7f4bd0dd0e87bddea622149a8c6e922ba475",
        "tarball": "https://registry.npmjs.org/javascripting/-/javascripting-2.6.1.tgz"
    },
    "gitHead": "b080365f9627e8876dfe63f2ed53e89ef735eb70",
    "homepage": "https://github.com/sethvincent/javascripting#readme",
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "julianduque",
            "email": "julianduquej@gmail.com"
        },
        {
            "name": "leichtgewicht",
            "email": "martin.heidegger@gmail.com"
        },
        {
            "name": "sethvincent",
            "email": "sethvincent@gmail.com"
        },
        {
            "name": "someoneweird",
            "email": "adam@boxxen.org"
        },
        {
            "name": "tdd",
            "email": "tdd@tddsworld.com"
        }
    ],
    "name": "javascripting",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "url": "git+https://github.com/sethvincent/javascripting.git"
    },
    "scripts": {},
    "version": "2.6.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module javascripting](#apidoc.module.javascripting)
1.  [function <span class="apidocSignatureSpan">javascripting.</span>__ ()](#apidoc.element.javascripting.__)
1.  [function <span class="apidocSignatureSpan">javascripting.</span>__n ()](#apidoc.element.javascripting.__n)
1.  number <span class="apidocSignatureSpan">javascripting.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">javascripting.</span>_events
1.  object <span class="apidocSignatureSpan">javascripting.</span>_meta
1.  object <span class="apidocSignatureSpan">javascripting.</span>appStorage
1.  object <span class="apidocSignatureSpan">javascripting.</span>cli
1.  object <span class="apidocSignatureSpan">javascripting.</span>domain
1.  object <span class="apidocSignatureSpan">javascripting.</span>exercises
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n.lookup
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n.mustache
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n.mustache.Context.prototype
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n.mustache.Scanner.prototype
1.  object <span class="apidocSignatureSpan">javascripting.</span>i18n.mustache.Writer.prototype
1.  object <span class="apidocSignatureSpan">javascripting.</span>options

#### [module javascripting.appStorage](#apidoc.module.javascripting.appStorage)
1.  [function <span class="apidocSignatureSpan">javascripting.appStorage.</span>get (name)](#apidoc.element.javascripting.appStorage.get)
1.  [function <span class="apidocSignatureSpan">javascripting.appStorage.</span>reset ()](#apidoc.element.javascripting.appStorage.reset)
1.  [function <span class="apidocSignatureSpan">javascripting.appStorage.</span>save (name, data)](#apidoc.element.javascripting.appStorage.save)
1.  string <span class="apidocSignatureSpan">javascripting.appStorage.</span>dir

#### [module javascripting.i18n](#apidoc.module.javascripting.i18n)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>__ ()](#apidoc.element.javascripting.i18n.__)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>__n ()](#apidoc.element.javascripting.i18n.__n)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>change (lng)](#apidoc.element.javascripting.i18n.change)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>changeLang (lang)](#apidoc.element.javascripting.i18n.changeLang)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>changePrefix ()](#apidoc.element.javascripting.i18n.changePrefix)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>extend (obj)](#apidoc.element.javascripting.i18n.extend)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>fallback (key)](#apidoc.element.javascripting.i18n.fallback)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>has (key)](#apidoc.element.javascripting.i18n.has)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>lang ()](#apidoc.element.javascripting.i18n.lang)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>raw (key)](#apidoc.element.javascripting.i18n.raw)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>sub ()](#apidoc.element.javascripting.i18n.sub)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>translate ()](#apidoc.element.javascripting.i18n.translate)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>translateFirst ()](#apidoc.element.javascripting.i18n.translateFirst)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.</span>vsprintf (fmt, argv)](#apidoc.element.javascripting.i18n.vsprintf)
1.  object <span class="apidocSignatureSpan">javascripting.i18n.</span>lookup
1.  object <span class="apidocSignatureSpan">javascripting.i18n.</span>mustache
1.  object <span class="apidocSignatureSpan">javascripting.i18n.</span>storage

#### [module javascripting.i18n.lookup](#apidoc.module.javascripting.i18n.lookup)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.lookup.</span>get (key)](#apidoc.element.javascripting.i18n.lookup.get)

#### [module javascripting.i18n.mustache](#apidoc.module.javascripting.i18n.mustache)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Context (view, parentContext)](#apidoc.element.javascripting.i18n.mustache.Context)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Scanner (string)](#apidoc.element.javascripting.i18n.mustache.Scanner)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Writer ()](#apidoc.element.javascripting.i18n.mustache.Writer)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>clearCache ()](#apidoc.element.javascripting.i18n.mustache.clearCache)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>escape (string)](#apidoc.element.javascripting.i18n.mustache.escape)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>parse (template, tags)](#apidoc.element.javascripting.i18n.mustache.parse)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>render (template, view, partials)](#apidoc.element.javascripting.i18n.mustache.render)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>to_html (template, view, partials, send)](#apidoc.element.javascripting.i18n.mustache.to_html)
1.  object <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>tags
1.  string <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>name
1.  string <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>version

#### [module javascripting.i18n.mustache.Context.prototype](#apidoc.module.javascripting.i18n.mustache.Context.prototype)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Context.prototype.</span>lookup (name)](#apidoc.element.javascripting.i18n.mustache.Context.prototype.lookup)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Context.prototype.</span>push (view)](#apidoc.element.javascripting.i18n.mustache.Context.prototype.push)

#### [module javascripting.i18n.mustache.Scanner.prototype](#apidoc.module.javascripting.i18n.mustache.Scanner.prototype)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>eos ()](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.eos)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>scan (re)](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scan)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>scanUntil (re)](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scanUntil)

#### [module javascripting.i18n.mustache.Writer.prototype](#apidoc.module.javascripting.i18n.mustache.Writer.prototype)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>clearCache ()](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.clearCache)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>parse (template, tags)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.parse)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>render (template, view, partials)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.render)
1.  [function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>renderTokens (tokens, context, partials, originalTemplate)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.renderTokens)



# <a name="apidoc.module.javascripting"></a>[module javascripting](#apidoc.module.javascripting)

#### <a name="apidoc.element.javascripting.__"></a>[function <span class="apidocSignatureSpan">javascripting.</span>__ ()](#apidoc.element.javascripting.__)
- description and source-code
```javascript
__ = function () { [native code] }
```
- example usage
```shell
...
 * @param {string} solutionPath
 * @param {!{__: function(string, object)}} i18n
 * @param {function} cb
 */
module.exports = function (solutionPath, i18n, cb) {
  exists(solutionPath).then(function(solutionExists) {
    if (!solutionExists) {
      throw new Error(i18n.__('error.exercise.missing_file', {exerciseFile: solutionPath}));
    }

    return executeSolution(solutionPath);
  }).then(function(stdout) {
    cb(null, stdout);
  }).catch(cb);
}
...
```

#### <a name="apidoc.element.javascripting.__n"></a>[function <span class="apidocSignatureSpan">javascripting.</span>__n ()](#apidoc.element.javascripting.__n)
- description and source-code
```javascript
__n = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.appStorage"></a>[module javascripting.appStorage](#apidoc.module.javascripting.appStorage)

#### <a name="apidoc.element.javascripting.appStorage.get"></a>[function <span class="apidocSignatureSpan">javascripting.appStorage.</span>get (name)](#apidoc.element.javascripting.appStorage.get)
- description and source-code
```javascript
function get(name) {
  var file = fileName(name)
  try {
    var fileData = fs.readFileSync(file, 'utf8')
  } catch (e) {
    // TODO: write this error in a log
    return null
  }
  try {
    return JSON.parse(fileData)
  } catch (e) {
    // TODO: write this error in a log
    return null
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.appStorage.reset"></a>[function <span class="apidocSignatureSpan">javascripting.appStorage.</span>reset ()](#apidoc.element.javascripting.appStorage.reset)
- description and source-code
```javascript
function reset() {
  rimraf.sync(dir)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.appStorage.save"></a>[function <span class="apidocSignatureSpan">javascripting.appStorage.</span>save (name, data)](#apidoc.element.javascripting.appStorage.save)
- description and source-code
```javascript
function save(name, data) {
  mkdirp.sync(dir)
  try {
    fs.writeFileSync(fileName(name), JSON.stringify(data, null, 2))
  } catch (e) {
    // TODO: write this error in a log
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n"></a>[module javascripting.i18n](#apidoc.module.javascripting.i18n)

#### <a name="apidoc.element.javascripting.i18n.__"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>__ ()](#apidoc.element.javascripting.i18n.__)
- description and source-code
```javascript
__ = function () { [native code] }
```
- example usage
```shell
...
 * @param {string} solutionPath
 * @param {!{__: function(string, object)}} i18n
 * @param {function} cb
 */
module.exports = function (solutionPath, i18n, cb) {
  exists(solutionPath).then(function(solutionExists) {
    if (!solutionExists) {
      throw new Error(i18n.__('error.exercise.missing_file', {exerciseFile: solutionPath}));
    }

    return executeSolution(solutionPath);
  }).then(function(stdout) {
    cb(null, stdout);
  }).catch(cb);
}
...
```

#### <a name="apidoc.element.javascripting.i18n.__n"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>__n ()](#apidoc.element.javascripting.i18n.__n)
- description and source-code
```javascript
__n = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.change"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>change (lng)](#apidoc.element.javascripting.i18n.change)
- description and source-code
```javascript
change = function (lng) {
  lang = choose(lng)
  translator.changeLang(lang)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.changeLang"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>changeLang (lang)](#apidoc.element.javascripting.i18n.changeLang)
- description and source-code
```javascript
function changeLang(lang) {
		result.changePrefix(lang + ".");
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.changePrefix"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>changePrefix ()](#apidoc.element.javascripting.i18n.changePrefix)
- description and source-code
```javascript
function changePrefix() {
			throw new Error("Forbidden by configuration");
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.extend"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>extend (obj)](#apidoc.element.javascripting.i18n.extend)
- description and source-code
```javascript
extend = function (obj) {
  return i18n(i18nExtend(result, {
    get: function (key) {
      return obj[key]
    }
  }))
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.fallback"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>fallback (key)](#apidoc.element.javascripting.i18n.fallback)
- description and source-code
```javascript
function defaultFallback(key) {
	if (!key) {
		return "(?)";
	}
	return key;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.has"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>has (key)](#apidoc.element.javascripting.i18n.has)
- description and source-code
```javascript
function has(key) {
	var val = this.raw(key);
	return val !== undefined && val !== null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.lang"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>lang ()](#apidoc.element.javascripting.i18n.lang)
- description and source-code
```javascript
lang = function () {
  return lang
}
```
- example usage
```shell
...
var problemName = dirname.split(path.sep);
var i18n;

problemName = problemName[problemName.length-1];

exports.init = function (workshopper) {
  i18n = workshopper.i18n;
  var postfix = workshopper.i18n.lang() === 'en' ? '' : '_' + workshopper.i18n.lang();
  this.problem  = {file: path.join(dirname, 'problem' + postfix + '.md')};
  this.solution = {file: path.join(dirname, 'solution' + postfix + '.md')};
  this.solutionPath = path.resolve(__dirname, '..', 'solutions', problemName, "index.js");
  this.troubleshootingPath = path.join(__dirname, '..', 'i18n', 'troubleshooting' + postfix + '.md');
}

exports.verify = function (args, cb) {
...
```

#### <a name="apidoc.element.javascripting.i18n.raw"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>raw (key)](#apidoc.element.javascripting.i18n.raw)
- description and source-code
```javascript
function raw(key) {
	return this.lookup.get(key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.sub"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>sub ()](#apidoc.element.javascripting.i18n.sub)
- description and source-code
```javascript
sub = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.translate"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>translate ()](#apidoc.element.javascripting.i18n.translate)
- description and source-code
```javascript
translate = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.translateFirst"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>translateFirst ()](#apidoc.element.javascripting.i18n.translateFirst)
- description and source-code
```javascript
translateFirst = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.vsprintf"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.</span>vsprintf (fmt, argv)](#apidoc.element.javascripting.i18n.vsprintf)
- description and source-code
```javascript
vsprintf = function (fmt, argv) {
	var argvClone = argv.slice();
	argvClone.unshift(fmt);
	return sprintf.apply(null, argvClone);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n.lookup"></a>[module javascripting.i18n.lookup](#apidoc.module.javascripting.i18n.lookup)

#### <a name="apidoc.element.javascripting.i18n.lookup.get"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.lookup.</span>get (key)](#apidoc.element.javascripting.i18n.lookup.get)
- description and source-code
```javascript
get = function (key) {
  return i18n.has(key) ? i18n.__(key) : lookup.get(key);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n.mustache"></a>[module javascripting.i18n.mustache](#apidoc.module.javascripting.i18n.mustache)

#### <a name="apidoc.element.javascripting.i18n.mustache.Context"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Context (view, parentContext)](#apidoc.element.javascripting.i18n.mustache.Context)
- description and source-code
```javascript
function Context(view, parentContext) {
  this.view = view == null ? {} : view;
  this.cache = { '.': this.view };
  this.parent = parentContext;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Scanner"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Scanner (string)](#apidoc.element.javascripting.i18n.mustache.Scanner)
- description and source-code
```javascript
function Scanner(string) {
  this.string = string;
  this.tail = string;
  this.pos = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Writer"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>Writer ()](#apidoc.element.javascripting.i18n.mustache.Writer)
- description and source-code
```javascript
function Writer() {
  this.cache = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.clearCache"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>clearCache ()](#apidoc.element.javascripting.i18n.mustache.clearCache)
- description and source-code
```javascript
clearCache = function () {
  return defaultWriter.clearCache();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.escape"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>escape (string)](#apidoc.element.javascripting.i18n.mustache.escape)
- description and source-code
```javascript
function escapeHtml(string) {
  return String(string).replace(/[&<>"'\/]/g, function (s) {
    return entityMap[s];
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.parse"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>parse (template, tags)](#apidoc.element.javascripting.i18n.mustache.parse)
- description and source-code
```javascript
parse = function (template, tags) {
  return defaultWriter.parse(template, tags);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.render"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>render (template, view, partials)](#apidoc.element.javascripting.i18n.mustache.render)
- description and source-code
```javascript
render = function (template, view, partials) {
  return defaultWriter.render(template, view, partials);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.to_html"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.</span>to_html (template, view, partials, send)](#apidoc.element.javascripting.i18n.mustache.to_html)
- description and source-code
```javascript
to_html = function (template, view, partials, send) {
  var result = mustache.render(template, view, partials);

  if (isFunction(send)) {
    send(result);
  } else {
    return result;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n.mustache.Context.prototype"></a>[module javascripting.i18n.mustache.Context.prototype](#apidoc.module.javascripting.i18n.mustache.Context.prototype)

#### <a name="apidoc.element.javascripting.i18n.mustache.Context.prototype.lookup"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Context.prototype.</span>lookup (name)](#apidoc.element.javascripting.i18n.mustache.Context.prototype.lookup)
- description and source-code
```javascript
lookup = function (name) {
  var value;
  if (name in this.cache) {
    value = this.cache[name];
  } else {
    var context = this;

    while (context) {
      if (name.indexOf('.') > 0) {
        value = context.view;

        var names = name.split('.'), i = 0;
        while (value != null && i < names.length) {
          value = value[names[i++]];
        }
      } else {
        value = context.view[name];
      }

      if (value != null) break;

      context = context.parent;
    }

    this.cache[name] = value;
  }

  if (isFunction(value)) {
    value = value.call(this.view);
  }

  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Context.prototype.push"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Context.prototype.</span>push (view)](#apidoc.element.javascripting.i18n.mustache.Context.prototype.push)
- description and source-code
```javascript
push = function (view) {
  return new Context(view, this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n.mustache.Scanner.prototype"></a>[module javascripting.i18n.mustache.Scanner.prototype](#apidoc.module.javascripting.i18n.mustache.Scanner.prototype)

#### <a name="apidoc.element.javascripting.i18n.mustache.Scanner.prototype.eos"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>eos ()](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.eos)
- description and source-code
```javascript
eos = function () {
  return this.tail === "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scan"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>scan (re)](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scan)
- description and source-code
```javascript
scan = function (re) {
  var match = this.tail.match(re);

  if (match && match.index === 0) {
    var string = match[0];
    this.tail = this.tail.substring(string.length);
    this.pos += string.length;
    return string;
  }

  return "";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scanUntil"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Scanner.prototype.</span>scanUntil (re)](#apidoc.element.javascripting.i18n.mustache.Scanner.prototype.scanUntil)
- description and source-code
```javascript
scanUntil = function (re) {
  var index = this.tail.search(re), match;

  switch (index) {
  case -1:
    match = this.tail;
    this.tail = "";
    break;
  case 0:
    match = "";
    break;
  default:
    match = this.tail.substring(0, index);
    this.tail = this.tail.substring(index);
  }

  this.pos += match.length;

  return match;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.javascripting.i18n.mustache.Writer.prototype"></a>[module javascripting.i18n.mustache.Writer.prototype](#apidoc.module.javascripting.i18n.mustache.Writer.prototype)

#### <a name="apidoc.element.javascripting.i18n.mustache.Writer.prototype.clearCache"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>clearCache ()](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.clearCache)
- description and source-code
```javascript
clearCache = function () {
  this.cache = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Writer.prototype.parse"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>parse (template, tags)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.parse)
- description and source-code
```javascript
parse = function (template, tags) {
  var cache = this.cache;
  var tokens = cache[template];

  if (tokens == null) {
    tokens = cache[template] = parseTemplate(template, tags);
  }

  return tokens;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Writer.prototype.render"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>render (template, view, partials)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.render)
- description and source-code
```javascript
render = function (template, view, partials) {
  var tokens = this.parse(template);
  var context = (view instanceof Context) ? view : new Context(view);
  return this.renderTokens(tokens, context, partials, template);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.javascripting.i18n.mustache.Writer.prototype.renderTokens"></a>[function <span class="apidocSignatureSpan">javascripting.i18n.mustache.Writer.prototype.</span>renderTokens (tokens, context, partials, originalTemplate)](#apidoc.element.javascripting.i18n.mustache.Writer.prototype.renderTokens)
- description and source-code
```javascript
renderTokens = function (tokens, context, partials, originalTemplate) {
  var buffer = '';

  // This function is used to render an arbitrary template
  // in the current context by higher-order sections.
  var self = this;
  function subRender(template) {
    return self.render(template, context, partials);
  }

  var token, value;
  for (var i = 0, len = tokens.length; i < len; ++i) {
    token = tokens[i];

    switch (token[0]) {
    case '#':
      value = context.lookup(token[1]);
      if (!value) continue;

      if (isArray(value)) {
        for (var j = 0, jlen = value.length; j < jlen; ++j) {
          buffer += this.renderTokens(token[4], context.push(value[j]), partials, originalTemplate);
        }
      } else if (typeof value === 'object' || typeof value === 'string') {
        buffer += this.renderTokens(token[4], context.push(value), partials, originalTemplate);
      } else if (isFunction(value)) {
        if (typeof originalTemplate !== 'string') {
          throw new Error('Cannot use higher-order sections without the original template');
        }

        // Extract the portion of the original template that the section contains.
        value = value.call(context.view, originalTemplate.slice(token[3], token[5]), subRender);

        if (value != null) buffer += value;
      } else {
        buffer += this.renderTokens(token[4], context, partials, originalTemplate);
      }

      break;
    case '^':
      value = context.lookup(token[1]);

      // Use JavaScript's definition of falsy. Include empty arrays.
      // See https://github.com/janl/mustache.js/issues/186
      if (!value || (isArray(value) && value.length === 0)) {
        buffer += this.renderTokens(token[4], context, partials, originalTemplate);
      }

      break;
    case '>':
      if (!partials) continue;
      value = isFunction(partials) ? partials(token[1]) : partials[token[1]];
      if (value != null) buffer += this.renderTokens(this.parse(value), context, partials, value);
      break;
    case '&':
      value = context.lookup(token[1]);
      if (value != null) buffer += value;
      break;
    case 'name':
      value = context.lookup(token[1]);
      if (value != null) buffer += mustache.escape(value);
      break;
    case 'text':
      buffer += token[1];
      break;
    }
  }

  return buffer;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
