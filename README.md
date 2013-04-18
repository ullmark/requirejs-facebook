requirejs-facebook
==================
load facebook with requirejs.

Usage
------
```javascript

require.config({
  paths: {
    facebook: 'components/requirejs-facebook/facebook'
  },

  facebook: {
    appId: 14,
    cookie: false,
    looging: false,
    status: true,
    xfbml: false,
    channelUrl: ''
  }
});

define(['facebook'], function(FB) {
  // do something...
  FB.api('/platform', function(response) {

  });
});

```