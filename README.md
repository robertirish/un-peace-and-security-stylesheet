# UN Peace and Security Stylesheet

Optimized CSS stylesheet for the UN Peace and Security website.

## Files

- `styles.css` - Full stylesheet with comments (1.4 MB)
- `styles.min.css` - Minified version for production (1.1 MB)

## Usage

Reference the raw GitHub file in your HTML:

```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/robertirish/un-peace-and-security-stylesheet/main/styles.min.css">
```

Or use jsDelivr CDN for better performance:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/robertirish/un-peace-and-security-stylesheet@main/styles.min.css">
```

## Optimizations Applied

- Extracted all embedded CSS from 124 HTML pages
- Deduplicated 45 unique CSS variations into single file
- Removed unnecessary `!important` declarations (reduced from 6,000+ to 4)
- Increased selector specificity where needed
- Preserved all original functionality
