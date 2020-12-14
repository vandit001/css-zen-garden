# CSS Zen Garden

This exercise is the classic [CSS Zen Garden][zen-garden-site] exercise under the creative commons license - your goal is to take this site and completely change the look and feel of it using CSS.

## Submission Guidelines

These guidelines are outlined in the comment at the top of the HTML file and come directly from CSS Zen Garden.

- CSS3? Of course! Prefix for ALL browsers where necessary.
- go responsive; test your layout at multiple screen sizes.
- your browser testing baseline: IE9+, recent Chrome/Firefox/Safari, and iOS/Android
- Graceful degradation is acceptable, and in fact highly encouraged.
- use classes for styling. Don't use ids.
- web fonts are cool, just make sure you have a license to share the files. Hosted services that are applied via the CSS file (ie. Google Fonts) will work fine, but most that require custom HTML won't. TypeKit is supported, see the readme on this page for usage instructions: https://github.com/mezzoblue/csszengarden.com/

And a few tips on building your CSS file:

- use :first-child, :last-child and :nth-child to get at non-classed elements
- use ::before and ::after to create pseudo-elements for extra styling
- use multiple background images to apply as many as you need to any element
- use the Kellum Method for image replacement, if still needed. http://goo.gl/GXxdI
- don't rely on the extra divs at the bottom. Use ::before and ::after instead.

## Getting Started

### Working in the Browser

For this exercise, we recommend working directly in your browser developer tools.  If you use a browser that isn't Chrome or Firefox, please check to see if the browser is Chromium-based (use the chrome directions) or not (feel free to find your own path to editing in the browser).

1. Open the [html](index.html) file in your favorite browser (this can be done by opening a file explorer and dragging the file to your browser).
2. Open your browser developer tools (both Chrome and Firefox use `F12`, but all browsers should also allow you to right click and then inspect an element).
3. Open the style editor/source files
   - Chrome: Within the developer tools, look for a tab named `Sources`
   - Firefox: Within the developer tools, look for a tab named `Style Editor`
4. (Chrome only) On the left side of the `Sources` pane, select `Filesystem` and then `Add to workspace`
5. (Chrome only)  Add this directory to your workspace and then allow the browser to have access to the files
6. (Chrome only)  Check to see if the HTML and CSS files have small green dots on the page symbols - if so, the source pages are linked!

### Working in an IDE

It is definitely possible to work on this from an IDE.  If you opt for this route, remember to reload your browser often.

[zen-garden-site]: http://www.csszengarden.com/
[zen-garden-github]: https://github.com/mezzoblue/csszengarden.com