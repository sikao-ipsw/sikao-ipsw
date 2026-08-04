---
layout: post
title:  "My Thoughts On Jekyll"
date:   2026-08-04 10:51 +0200 
categories: web-development
---

For about a year, I have been using Astro as my framework for developing static websites. I enjoyed using it because it is like plain HTML, but better in many ways.

For example, if I have some code that's being reused a lot, I can turn it into a component in ``src/components/`` and import it anywhere I want. (Note: _Jekyll does not really use components, but you don't need them anyway in a plain-text based site_)

```jsx
---
import Component from '../components/component.astro';
---

<Component />
```

It also ships no JS to the client (_by default_), so it is very performant.

And another benefit is Markdown support, so you can write (.md or .mdx) pages in Markdown and it will just work. However, it is a bit too much for a personal website and blog. That's why I decided to switch to Jekyll for this website. It comes with everything you need to get started. Everything comes premade, all you need to do is write the content (and maybe customise the site a bit). RSS is also supported out of the box which is genuinely great.

So in conclusion, Next.js for anything interactive, Astro for anything static AND needs good UI (like a marketing page), and finally, Jekyll for anything mainly text and a UI wrapping it.
