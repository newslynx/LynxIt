LynxIt
===

A bookmarket for jumping to the NewsLynx page of an article you're currently viewing.


### Installation

Go to the [demo page](http://newslynx.github.io/LynxIt) and drag the bookmark to your bookmarks bar.

Or, make a new bookmark with the following url

````
javascript:(function(){var e="http://0.0.0.0:3000";window.location.replace(e+"/articles/lookup?url="+window.location.href)}).call(this)
````


TODO, change the domain to the final NewsLynx domain on launch.
