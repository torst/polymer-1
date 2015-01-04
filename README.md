Mobile DC
=======

Polymer Meetup - Jan 2014
-------

Prerequisites
-------
* *nix OS
* NodeJS
* Bower

System Setup
-------
* `$ git clone https://github.com/mobiledc/polymer`
* `$ cd polymer`
* `$ npm install`
* `$ cd example-simple/public`
* `$ bower install`
* `$ cd example-advanced/public`
* `$ bower install`

Running the Examples
-------

Simple Examples
======
* `$ cd example-simple`
* `$ node index.js`
* Single element example: launch Chrome and navigate to `http://localhost:5000/index-single.html`
* Nested elements example: launch Chrome and navigate to `http://localhost:5000/index-nested.html`

Advanced Example
======
* `$ cd example-advanced`
* `$ node index.js`
* Single element example: launch Chrome and navigate to `http://localhost:5000/index.html`

Add Your Import.IO API Keys
======
* `$ cd example-advanced/public/js`
* Edit `apikeys.js` like so:

```javascript
var IMPORT_IO_KEYS = {
    userGuid    : "YOUR_USER_GUID",
    apiKey      : "YOUR_API_KEY",
    sourceGuid  : "DATA_SOURCE_GUID"
};
```
