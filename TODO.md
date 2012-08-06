TODO
====

option page:

* Checkbox: Only replace scrollbars on websites which use default scrollbars. E.g. Gmail and Google Reader will not be affected. 
  - Use programmatic injection. Put a little JS code in all the pages. Read all $('style'), and test /::-webkit-scrollbar/ in them. If not found, insert the CSS file. CSS might be generated according to options saved in local storage. 

* Default styles: 
  - Simplistic
  - Mac
  - Google (Gmail, Google Reader)
  - Ubuntu (what is the style called?)

add a link to option page in context menu: customize styish scroll

http://css-tricks.com/custom-scrollbars-in-webkit/
http://css-tricks.com/examples/WebKitScrollbars/
http://glazkov.com/2011/01/14/what-the-heck-is-shadow-dom/
http://trac.webkit.org/export/41842/trunk/LayoutTests/scrollbars/overflow-scrollbar-combinations.html


Is there a way to detect color scheme of a webpage? If yes, consider setting scrollbar color accordingly. 


* Insert into iframes