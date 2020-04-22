# The Wayang Progress Bar

On occasions when the page is projected to load somewhat slowly, a progress bar is useful for encouraging patience in users. However, a loading icon is insufficient since this gives users very little insight as to how much of the page has loaded. The HTML, CSS and JavaScript simulate progress percentage, but it is *only* a simulation, hence the term *Wayang*.

It is programmed to come onscreen as soon as the page starts loading, and disappear when the page is finished loading. In cases where the bar reaches 100% before the page is done loading, it goes back to 90-plus percent, thus going on perpetually.

This is a harmless deception, though in the case of pages taking more than, say, 20 seconds, you are encouraged to take concrete steps to reduce loading time rather than depend on this progress loader.
