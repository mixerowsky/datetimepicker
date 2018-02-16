# PLEASE. Help me update documentation.
[Doc.tpl](https://github.com/xdan/datetimepicker/blob/master/doc.tpl)
This file will be automatically displayed on the site

# Installation

```
npm install jquery-datetimepicker
OR
yarn add jquery-datetimepicker
```

# datetimepicker
==============

**!!! The latest version of the options 'lang' obsolete. The language setting is now global. !!!**

Use this:
```javascript
jQuery.datetimepicker.setLocale('en');
```
[Documentation][doc]

jQuery Plugin Date and Time Picker

DateTimePicker

![ScreenShot](https://raw.github.com/xdan/datetimepicker/master/screen/1.png)

DatePicker

![ScreenShot](https://raw.github.com/xdan/datetimepicker/master/screen/2.png)

TimePicker

![ScreenShot](https://raw.github.com/xdan/datetimepicker/master/screen/3.png)

Options to highlight individual dates or periods

![ScreenShot](https://raw.github.com/Mingpao/datetimepicker/master/screen/4.png)

![ScreenShot](https://raw.github.com/Mingpao/datetimepicker/master/screen/5.png)

![ScreenShot](https://raw.github.com/Mingpao/datetimepicker/master/screen/6.png)

[doc]: http://xdsoft.net/jqplugins/datetimepicker/

### JS Build help

**Requires Node and NPM** [Download and install node.js](http://nodejs.org/download/).


Install:

1. Install `bower` globally with `npm install -g bower`.
2. Run `npm install`. npm will look at `package.json` and automatically install the necessary dependencies. 
3. Run `bower install`, which installs front-end packages defined in `bower.json`.

Notice: If you use Bower v1.5.2, you will get error: `The "main" field cannot contain minified files`
You can regress to version 1.3.12

1. `npm uninstall bower -g`
2. `npm install -g bower@1.3.12`

Build:

- `npm run build`

When build completed, you'll have the following files:
- **build/jquery.datetimepicker.full.js** - browser file
- **build/jquery.datetimepicker.full.min.js** - browser minified file
- **build/jquery.datetimepicker.min.js** - amd module style minified file
