Framework7 Indexed List Plugin
=============================
Demo: https://boynet.github.io/boynet/


This plugin is for Indexed-List scroll like iOS and Android have, currently works only with Contacts List

![''](http://i58.tinypic.com/2608tmo.jpg)


## Installation

And link them to your app's right AFTER Framework7's scripts and styles:

```html
<link rel="stylesheet" href="path/to/framework7.min.css">
<link rel="stylesheet" href="path/to/framework7.indexed-list.css">
...
<script src="path/to/framework7.min.js"></script>
<script src="path/to/framework7.indexed-list.js"></script>
```

## Usage
 put this html code inside `.page`
````html
<ul class="list-index"></ul>
````

 init the plugin, `.page` is the parent container of `.list-index`
```js
var myApp = new Framework7({
    indexedlist:{
        init:true,
        container:'.page'
    }
});
````
## Demo:
https://boynet.github.io/boynet/
