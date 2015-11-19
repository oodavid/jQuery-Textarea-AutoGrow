# jQuery Textarea AutoGrow

Automatically grows <textarea> elements (vertically) to accommodate its content. Has a minimum and maximum height and can trigger a callback when the size changes.

## Usage

```javascript
$('textarea').autoGrow({
     minHeight: 1,    // Min height (px), defaults to 1
     maxHeight: 1000, // Max height (px), defaults to 1000
     callback:  func  // Callback function, defaults to null
});
```

## Demo

Go to [oodavid.com/jQueryFaviconNotifier](http://oodavid.com/jQueryTextareaAutogrow/) (and read the source code).

![screenshot of it in action](http://oodavid.com/jQueryFaviconNotifier/screenshot.png)