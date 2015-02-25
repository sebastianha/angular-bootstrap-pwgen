angular-bootstrap-pwgen
=======================

An animated password generator for AngularJS styled to fit the Twitter Bootstrap standard design

Screenshot:

![Screenshot](/pwgen.gif?raw=true "Password generator in action")

### Installation via Bower:

```
$ bower install angular-bootstrap-pwgen --save
```

### Usage:

Add "ui.pwgen" to your modules list. Then you can use it like follows:

```
<pwgen
    ng-model="passwordModel"
    length="20"                 (Optional)
    placeholder="Password"      (Optional)
    ng-disabled="true"          (Optional)
></pwgen>
```

See index.html and app.js for examples and how it works.

Use ngAnimate for activate fade-in and fade-out of the progress bar while generating.

### Testing:

Start web server e.g. via Python:
```
$ python -m SimpleHTTPServer 8000
```

Start Karma E2E tests (has to be installed globally before):
```
$ karma start
```

### License

Copyright (c) 2014 Sebastian Hammerl, Getslash GmbH

Licensed under the MIT License