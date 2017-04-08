# api documentation for  [laravel-elixir (v5.0.0)](https://github.com/laravel/elixir)  [![npm package](https://img.shields.io/npm/v/npmdoc-laravel-elixir.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-laravel-elixir) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-laravel-elixir.svg)](https://travis-ci.org/npmdoc/node-npmdoc-laravel-elixir)
#### Laravel Elixir Core

[![NPM](https://nodei.co/npm/laravel-elixir.png?downloads=true)](https://www.npmjs.com/package/laravel-elixir)

[![apidoc](https://npmdoc.github.io/node-npmdoc-laravel-elixir/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-laravel-elixir%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-laravel-elixir/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-laravel-elixir/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-laravel-elixir/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Taylor Otwell, Jeffrey Way"
    },
    "bugs": {
        "url": "https://github.com/laravel/elixir/issues"
    },
    "dependencies": {
        "babel-preset-es2015": "^6.1.0",
        "babel-preset-react": "^6.1.18",
        "babelify": "^7.2.0",
        "browser-sync": "^2.7.10",
        "browserify": "^11.2.0",
        "del": "^1.2.0",
        "glob": "^5.0.14",
        "gulp-autoprefixer": "^2.3.1",
        "gulp-babel": "^6.1.0",
        "gulp-batch": "^1.0.5",
        "gulp-coffee": "^2.3.1",
        "gulp-concat": "^2.6.0",
        "gulp-cssnano": "^2.0.0",
        "gulp-if": "^1.2.5",
        "gulp-less": "^3.0.3",
        "gulp-load-plugins": "^1.0.0-rc.1",
        "gulp-notify": "^2.2.0",
        "gulp-rename": "^1.2.2",
        "gulp-rev": "^5.1.0",
        "gulp-rev-replace": "^0.4.2",
        "gulp-sass": "^2.0.3",
        "gulp-shell": "^0.5.0",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-uglify": "^1.5.1",
        "gulp-util": "^3.0.6",
        "gulp-watch": "^4.2.4",
        "insert-css": "^0.2.0",
        "merge-stream": "^0.1.8",
        "parse-filepath": "^0.5.0",
        "partialify": "^3.1.3",
        "path": "^0.11.14",
        "require-dir": "^0.3.0",
        "run-sequence": "^1.1.1",
        "underscore": "^1.8.3",
        "underscore-deep-extend": "0.0.5",
        "vinyl-buffer": "^1.0.0",
        "vinyl-paths": "^1.0.0",
        "vinyl-source-stream": "^1.1.0",
        "watchify": "^3.2.3"
    },
    "description": "Laravel Elixir Core",
    "devDependencies": {
        "chai": "^3.2.0",
        "gulp": "^3.8.8",
        "mocha": "^2.2.5",
        "rimraf": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "742f0d8676ef0db3d853f0620c996a5f6330e265",
        "tarball": "https://registry.npmjs.org/laravel-elixir/-/laravel-elixir-5.0.0.tgz"
    },
    "gitHead": "2def8c99ddc4aef42de981b175198e550ee8a9d2",
    "homepage": "https://github.com/laravel/elixir",
    "keywords": [
        "laravel",
        "elixir",
        "gulp"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jeffreyway",
            "email": "jeffrey@laracasts.com"
        }
    ],
    "name": "laravel-elixir",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/laravel/elixir.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "5.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module laravel-elixir](#apidoc.module.laravel-elixir)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>GulpPaths ()](#apidoc.element.laravel-elixir.GulpPaths)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>Logger ()](#apidoc.element.laravel-elixir.Logger)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>Notification ()](#apidoc.element.laravel-elixir.Notification)
1.  object <span class="apidocSignatureSpan">laravel-elixir.</span>Config
1.  object <span class="apidocSignatureSpan">laravel-elixir.</span>GulpPaths.prototype
1.  object <span class="apidocSignatureSpan">laravel-elixir.</span>Notification.prototype

#### [module laravel-elixir.Config](#apidoc.module.laravel-elixir.Config)
1.  boolean <span class="apidocSignatureSpan">laravel-elixir.Config.</span>production
1.  boolean <span class="apidocSignatureSpan">laravel-elixir.Config.</span>sourcemaps
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Config.</span>get (path)](#apidoc.element.laravel-elixir.Config.get)
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>batchOptions
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>browserSync
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>css
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>js
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>tasks
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>testing
1.  object <span class="apidocSignatureSpan">laravel-elixir.Config.</span>versioning
1.  string <span class="apidocSignatureSpan">laravel-elixir.Config.</span>appPath
1.  string <span class="apidocSignatureSpan">laravel-elixir.Config.</span>assetsPath
1.  string <span class="apidocSignatureSpan">laravel-elixir.Config.</span>publicPath
1.  string <span class="apidocSignatureSpan">laravel-elixir.Config.</span>viewPath

#### [module laravel-elixir.GulpPaths](#apidoc.module.laravel-elixir.GulpPaths)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>GulpPaths ()](#apidoc.element.laravel-elixir.GulpPaths.GulpPaths)

#### [module laravel-elixir.GulpPaths.prototype](#apidoc.module.laravel-elixir.GulpPaths.prototype)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>changeExtension (path, newExtension)](#apidoc.element.laravel-elixir.GulpPaths.prototype.changeExtension)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>output (output, defaultName)](#apidoc.element.laravel-elixir.GulpPaths.prototype.output)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>parse (path)](#apidoc.element.laravel-elixir.GulpPaths.prototype.parse)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>prefix (path, prefix)](#apidoc.element.laravel-elixir.GulpPaths.prototype.prefix)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>src (src, prefix)](#apidoc.element.laravel-elixir.GulpPaths.prototype.src)

#### [module laravel-elixir.Logger](#apidoc.module.laravel-elixir.Logger)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>Logger ()](#apidoc.element.laravel-elixir.Logger.Logger)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>files (files, checkForFiles)](#apidoc.element.laravel-elixir.Logger.files)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>heading (heading)](#apidoc.element.laravel-elixir.Logger.heading)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>message (message)](#apidoc.element.laravel-elixir.Logger.message)

#### [module laravel-elixir.Notification](#apidoc.module.laravel-elixir.Notification)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.</span>Notification ()](#apidoc.element.laravel-elixir.Notification.Notification)

#### [module laravel-elixir.Notification.prototype](#apidoc.module.laravel-elixir.Notification.prototype)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>error (e, message)](#apidoc.element.laravel-elixir.Notification.prototype.error)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>forFailedTests (e, framework)](#apidoc.element.laravel-elixir.Notification.prototype.forFailedTests)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>forPassedTests (framework)](#apidoc.element.laravel-elixir.Notification.prototype.forPassedTests)
1.  [function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>message (message)](#apidoc.element.laravel-elixir.Notification.prototype.message)



# <a name="apidoc.module.laravel-elixir"></a>[module laravel-elixir](#apidoc.module.laravel-elixir)

#### <a name="apidoc.element.laravel-elixir.GulpPaths"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>GulpPaths ()](#apidoc.element.laravel-elixir.GulpPaths)
- description and source-code
```javascript
GulpPaths = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Logger"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>Logger ()](#apidoc.element.laravel-elixir.Logger)
- description and source-code
```javascript
Logger = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Notification"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>Notification ()](#apidoc.element.laravel-elixir.Notification)
- description and source-code
```javascript
Notification = function () {
    this.title = 'Laravel Elixir';

    // If an argument is provided, then we'll
    // assume they want to show a message.
    if (arguments.length) {
        return this.message(arguments[0]);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.laravel-elixir.Config"></a>[module laravel-elixir.Config](#apidoc.module.laravel-elixir.Config)

#### <a name="apidoc.element.laravel-elixir.Config.get"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Config.</span>get (path)](#apidoc.element.laravel-elixir.Config.get)
- description and source-code
```javascript
get = function (path) {
    var basePath;
    var current = config;

    var segments = path.split('.');

    // If the path begins with "assets" or "public," then
    // we can assume that the user wants to prefix the
    // given base url to their config path. Useful!

    if (segments[0] == 'assets' || segments[0] == 'public') {
        basePath = config[segments.shift()+'Path'];
    }

    segments.forEach(function(segment) {
        current = current[segment];
    });

    return p.join(basePath, current);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.laravel-elixir.GulpPaths"></a>[module laravel-elixir.GulpPaths](#apidoc.module.laravel-elixir.GulpPaths)

#### <a name="apidoc.element.laravel-elixir.GulpPaths.GulpPaths"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>GulpPaths ()](#apidoc.element.laravel-elixir.GulpPaths.GulpPaths)
- description and source-code
```javascript
GulpPaths = function () {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.laravel-elixir.GulpPaths.prototype"></a>[module laravel-elixir.GulpPaths.prototype](#apidoc.module.laravel-elixir.GulpPaths.prototype)

#### <a name="apidoc.element.laravel-elixir.GulpPaths.prototype.changeExtension"></a>[function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>changeExtension (path, newExtension)](#apidoc.element.laravel-elixir.GulpPaths.prototype.changeExtension)
- description and source-code
```javascript
changeExtension = function (path, newExtension) {
    return gutils.replaceExtension(path, newExtension);
}
```
- example usage
```shell
...
// then we'll do our best to choose a default.
if ( ! this.output.name && defaultName) {
    // We'll check to see if the provided src is not
    // an array. If so, we'll use that single file
    // name as the output name. But we must also
    // change the extension (.sass -> .css).
    if ( ! Array.isArray(this.src.path) && this.src.name.indexOf('*') == -1) {
        defaultName = this.changeExtension(
            this.src.name,
            this.parse(defaultName).extension
        );
    }

    this.output = this.parse(p.join(output, defaultName));
}
...
```

#### <a name="apidoc.element.laravel-elixir.GulpPaths.prototype.output"></a>[function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>output (output, defaultName)](#apidoc.element.laravel-elixir.GulpPaths.prototype.output)
- description and source-code
```javascript
output = function (output, defaultName) {
    this.output = this.parse(output);

    // If the user didn't provide a path AND file name
    // then we'll do our best to choose a default.
    if ( ! this.output.name && defaultName) {
        // We'll check to see if the provided src is not
        // an array. If so, we'll use that single file
        // name as the output name. But we must also
        // change the extension (.sass -> .css).
        if ( ! Array.isArray(this.src.path) && this.src.name.indexOf('*') == -1) {
            defaultName = this.changeExtension(
                this.src.name,
                this.parse(defaultName).extension
            );
        }

        this.output = this.parse(p.join(output, defaultName));
    }

    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.GulpPaths.prototype.parse"></a>[function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>parse (path)](#apidoc.element.laravel-elixir.GulpPaths.prototype.parse)
- description and source-code
```javascript
parse = function (path) {
    var segments = parsePath(path);

    return {
        path      : path,
        name      : segments.extname ? segments.basename : '',
        extension : segments.extname,
        isDir     : ! (!! segments.extname),
        baseDir   : segments.extname
                        ? segments.dirname
                        : p.join(segments.dirname, segments.basename)
    };
}
```
- example usage
```shell
...
 *
 * @param {string} file
 */
Elixir.setDefaultsFrom = function(file) {
var overrides;

if (fs.existsSync(file)) {
    overrides = JSON.parse(fs.readFileSync(file, 'utf8'));

    _.mixin({
        deepExtend: require('underscore-deep-extend')(_)
    });

    _.deepExtend(Elixir.config, overrides);
}
...
```

#### <a name="apidoc.element.laravel-elixir.GulpPaths.prototype.prefix"></a>[function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>prefix (path, prefix)](#apidoc.element.laravel-elixir.GulpPaths.prototype.prefix)
- description and source-code
```javascript
prefix = function (path, prefix) {
    if ( ! prefix) return path;

    var prefixOne = function(path) {
        // Given any path that begins with a period, we
        // can safely assume that the user wants to
        // skip the prefix and begin at the root.
        if (path.indexOf('./') == 0) {
            return path;
        }

        // If path starts with "!" we need to negate him
        if (path.indexOf('!') == 0) {
            path = '!' + p.join(prefix, path.substring(1));
        } else {
            path = p.join(prefix, path);
        }

        return path.replace(/\/\//g, '/')
            .replace(/\/\//g, '/')
            .replace(p.join(prefix, prefix), prefix);
    };

    if (Array.isArray(path)) {
        return path.map(prefixOne);
    }

    return prefixOne(path);
}
```
- example usage
```shell
...
 * @param  {string|Array} src
 * @param  {string|null}  prefix
 * @return {GulpPaths}
 */
GulpPaths.prototype.src = function(src, prefix) {
var self = this;

src = this.prefix(src, prefix);

if (Array.isArray(src)) {
    // If any item in the src array is a folder
    // then we will fetch all of the files.
    src = src.map(function(path) {
        if (self.parse(path).isDir) {
            path += '/**/*';
...
```

#### <a name="apidoc.element.laravel-elixir.GulpPaths.prototype.src"></a>[function <span class="apidocSignatureSpan">laravel-elixir.GulpPaths.prototype.</span>src (src, prefix)](#apidoc.element.laravel-elixir.GulpPaths.prototype.src)
- description and source-code
```javascript
src = function (src, prefix) {
    var self = this;

    src = this.prefix(src, prefix);

    if (Array.isArray(src)) {
        // If any item in the src array is a folder
        // then we will fetch all of the files.
        src = src.map(function(path) {
            if (self.parse(path).isDir) {
                path += '/**/*';
            }

            return path;
        });

        this.src = { path: src, baseDir: prefix };
    } else {
        this.src = this.parse(src);

        // If a directory is provided as the Gulp src,
        // the user probably wants everything in it.
        this.src.isDir && (this.src.path += '/**/*');
    }

    return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.laravel-elixir.Logger"></a>[module laravel-elixir.Logger](#apidoc.module.laravel-elixir.Logger)

#### <a name="apidoc.element.laravel-elixir.Logger.Logger"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>Logger ()](#apidoc.element.laravel-elixir.Logger.Logger)
- description and source-code
```javascript
Logger = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Logger.files"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>files (files, checkForFiles)](#apidoc.element.laravel-elixir.Logger.files)
- description and source-code
```javascript
files = function (files, checkForFiles) {
    files = Array.isArray(files) ? files : [files];
    var spacer = '   - ';

    files.forEach(function(file) {
        if ( ! checkForFiles || assertFileExists(file)) {
            console.log(spacer + file);
        } else {
            console.log(spacer + gutil.colors.bgRed(file) + ' <-- Not Found');
        }
    });

    console.log(); // For a line break.

    return Logger;
}
```
- example usage
```shell
...
 * @param {string|null}  output
 */
Task.prototype.log = function(src, output) {
    var task = this.name.substr(0,1).toUpperCase() + this.name.substr(1);

    Elixir.Log
       .heading("Fetching " + task + " Source Files...")
       .files(src.path ? src.path : src, true);

    if (output) {
        Elixir.Log
            .heading('Saving To...')
            .files(output.path ? output.path : output);
    }
};
...
```

#### <a name="apidoc.element.laravel-elixir.Logger.heading"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>heading (heading)](#apidoc.element.laravel-elixir.Logger.heading)
- description and source-code
```javascript
heading = function (heading) {
    console.log(''); // line break

    console.log(
        gutil.colors.black(gutil.colors.bgGreen(heading))
    );

    return Logger;
}
```
- example usage
```shell
...
 * @param {string|Array} src
 * @param {string|null}  output
 */
Task.prototype.log = function(src, output) {
var task = this.name.substr(0,1).toUpperCase() + this.name.substr(1);

Elixir.Log
   .heading("Fetching " + task + " Source Files...")
   .files(src.path ? src.path : src, true);

if (output) {
    Elixir.Log
        .heading('Saving To...')
        .files(output.path ? output.path : output);
}
...
```

#### <a name="apidoc.element.laravel-elixir.Logger.message"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Logger.</span>message (message)](#apidoc.element.laravel-elixir.Logger.message)
- description and source-code
```javascript
message = function (message) {
    console.log(message);

    return Logger;
}
```
- example usage
```shell
...
*/
var Notification = function() {
   this.title = 'Laravel Elixir';

   // If an argument is provided, then we'll
   // assume they want to show a message.
   if (arguments.length) {
       return this.message(arguments[0]);
   }
};

var n = Notification.prototype;

/**
* Display a notification.
...
```



# <a name="apidoc.module.laravel-elixir.Notification"></a>[module laravel-elixir.Notification](#apidoc.module.laravel-elixir.Notification)

#### <a name="apidoc.element.laravel-elixir.Notification.Notification"></a>[function <span class="apidocSignatureSpan">laravel-elixir.</span>Notification ()](#apidoc.element.laravel-elixir.Notification.Notification)
- description and source-code
```javascript
Notification = function () {
    this.title = 'Laravel Elixir';

    // If an argument is provided, then we'll
    // assume they want to show a message.
    if (arguments.length) {
        return this.message(arguments[0]);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.laravel-elixir.Notification.prototype"></a>[module laravel-elixir.Notification.prototype](#apidoc.module.laravel-elixir.Notification.prototype)

#### <a name="apidoc.element.laravel-elixir.Notification.prototype.error"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>error (e, message)](#apidoc.element.laravel-elixir.Notification.prototype.error)
- description and source-code
```javascript
error = function (e, message) {
    notify.onError({
        title: this.title,
        message: message + ': <%= error.message %>',
        icon: __dirname + '/icons/fail.png',
        onLast: true
    })(e);

    // We'll spit out the error, just in
    // case it is useful for the user.
    console.log(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Notification.prototype.forFailedTests"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>forFailedTests (e, framework)](#apidoc.element.laravel-elixir.Notification.prototype.forFailedTests)
- description and source-code
```javascript
forFailedTests = function (e, framework) {
    return notify.onError({
        title: 'Red!',
        message: 'Your ' + framework + ' tests failed!',
        icon: __dirname + '/icons/fail.png',
        onLast: true
    })(e);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Notification.prototype.forPassedTests"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>forPassedTests (framework)](#apidoc.element.laravel-elixir.Notification.prototype.forPassedTests)
- description and source-code
```javascript
forPassedTests = function (framework) {
    return notify({
        title: 'Green!',
        message: 'Your ' + framework + ' tests passed!',
        icon: __dirname + '/icons/pass.png',
        onLast: true
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.laravel-elixir.Notification.prototype.message"></a>[function <span class="apidocSignatureSpan">laravel-elixir.Notification.prototype.</span>message (message)](#apidoc.element.laravel-elixir.Notification.prototype.message)
- description and source-code
```javascript
message = function (message) {
    return notify({
        title: this.title,
        message: message,
        icon: __dirname + '/icons/laravel.png',
        onLast: true
    });
}
```
- example usage
```shell
...
*/
var Notification = function() {
   this.title = 'Laravel Elixir';

   // If an argument is provided, then we'll
   // assume they want to show a message.
   if (arguments.length) {
       return this.message(arguments[0]);
   }
};

var n = Notification.prototype;

/**
* Display a notification.
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
