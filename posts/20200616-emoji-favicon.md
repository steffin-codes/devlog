---
title: Emoji Favicon
excerpt: "Small html snippet to make favicons using emoji :)"
favicon: 🥳
tags: snippet
---

Thought this would be a nice way to have fun with the blogs metadata 🤪 Check the evechanging emoji favicon on my blog posts :) More on how to implement this in Next.js later

For now ...

Add this to your `head`

```html
<link
    rel="icon"
    href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>📜</text></svg>"
    />
```

## Related links to explain:
- [CSS tricks](https://css-tricks.com/emojis-as-favicons/)
- [tweet](https://twitter.com/LeaVerou/status/1241619866475474946?s=20)
- [demo](https://000458870.codepen.website/)