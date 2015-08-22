# Fullscreen.js
Fullscreen mode for web browsers

### Installation
    npm install --save fullscreenjs

### JSLint
To test Fullscreen.js, use `jslint --browser --sloppy fullscreen.js`.

### Usage
Fullscreen.js should be pretty self-explanatory from the function comments; all
you have to do to include it in your project is:

    <script src="fullscreen.js"></script>

from some HTML file, in the `<head>` tag, before you use any of the library's
functions.

You can also use `require()` as supplied by Node.js-style module systems if you
use NPM, like so:

    var fs = require('fullscreenjs');
