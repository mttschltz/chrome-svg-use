# chrome-svg-use
In Chrome (Windows/40.0.2214.93 m) the following line, pointing to a fragment identifier in an SVG file, causes Chrome to scroll to the element:

    <object type="image/svg+xml" data="test.svg#rectangle"></object>


Demo: [http://mttschltz.github.io/chrome-svg-use](http://mttschltz.github.io/chrome-svg-use).

Bug report: https://code.google.com/p/chromium/issues/detail?id=452854
