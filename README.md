lodash-angular-wrapper
======================

This is simple module for wrap Lo-dash (http://lodash.com/) lib in angular service. 

Installing
======================

Install via bower

`bower install lodash-angular-wrapper`

Require it into your application (after Angular anf Lo-dash)

`<script src="lodash-angular-wrapper.js"></script>`

Add the module as a dependency to your app

`var app = angular.module('yourApp', ['lodashAngularWrapper']);`

Then inject it into your controller

```
var MainCtrl = app.controller('yourAppMainController', function($scope, _) {
  _.assign({ 'a1': 1 }, { 'a2': 2 }, { 'a3': 3 });
});
```

