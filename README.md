InstantClick
---

This is a slightly modified version of InstantClick 3.1.0. It makes it easier to prevent InstantClick from loading a page under certain conditions.

Additions in this version:
- Add a `data-instant-manual` attribute to a link to prevent the regular InstantClick event handler from working. Preloading will still work.
- Trigger the `InstantClick.openLink(href)` function to manually load a page. 
- If you send an `X-Canonical-URL` header, InstantClick will display that URL and use it for history instead of the URL it originally navigated to. This helps you deal with issues that pop up when you redirect users with a `Location` header, for instance.

License
---
Copyright (c) 2014, 2015 Alexandre Dieulot

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
