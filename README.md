# UX and UI Best Practices for PWAs
UX and UI Best Practices for PWAs

## UI Basics 

### App icons
- Design and set app icons 
- Do I have the right icon sizes to trigger an install prompt?
- Maskable icons | [Information](https://web.dev/maskable-icon/)
)

### Define a theme color

- Is my theme color set in my web app manifest?
- Do I need to provide a meta tag in my HTML?

### Using system fonts
- Do I have my `font-family` set to `system-ui` for my installed PWA?

## Responsive considerations 

### Display modes & Window controls overlay
- What display mode do I want for my PWA?
- If I'm using `fullscreen` or `standalone` have I provide sufficient navigation in my UI?
- Am I using media queries to serve up specific styles or UI elements for targeted display modes?
- Is there any content I can include in my titlebar and utilize Window controls overlay?

## UX Considerations 

### Go lite and prioritize content 
- What are the top tasks my users are trying to complete?
- How can I streamline those tasks?
- Can I keep important UI elements constantly available?
- How can I reduce content clutter in my PWA? 
- Did I use media queries to remove the footer in certain display modes?

### Make interactions seamless and fast 
- Do I need to use a skeleton screen for loading elements?
- If yes, test. 

- Do I provide interaction feedback when UI elements are interacted with?
- Have I leveraged platform features that speed up tasks? [What PWA Can Do Today](https://whatpwacando.today/)

### Offline mode

- Your PWA should have an offline experience so...
- What's my offline strategy?
- Custom offline page or proactively cached content?


