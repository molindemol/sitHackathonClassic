# Useful websites

Stuck? Curious? These sites are the ones we would open ourselves. Everything here is free, needs no account, and works for the plain HTML, CSS and JavaScript used in the templates.

Read this list top to bottom once. Then keep MDN and CSS-Tricks open in a tab while you build.

## Look things up

| Site | What it is good for |
|---|---|
| [MDN Web Docs](https://developer.mozilla.org/) | The reference for HTML, CSS and JavaScript. Search "mdn" plus the thing you want, for example `mdn addEventListener`. Trust this over random blogs. |
| [javascript.info](https://javascript.info/) | JavaScript explained step by step with small examples. Good if you want to understand why something works, not only how. |
| [W3Schools](https://www.w3schools.com/) | Short pages with a "Try it yourself" button. Less precise than MDN but faster to read. |
| [Can I use](https://caniuse.com/) | Check if a CSS or JS feature works in the browser you are using. Mostly yes these days. |
| [DevDocs](https://devdocs.io/) | All documentation in one searchable page. Works offline once loaded. |

## CSS and layout

| Site | What it is good for |
|---|---|
| [CSS-Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) | The templates use `display: flex` a lot. This page shows every option with a picture. |
| [CSS-Tricks: A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) | Same thing for `display: grid`, used in the profile page cards. |
| [Flexbox Froggy](https://flexboxfroggy.com/) | A game that teaches flexbox. Takes 20 minutes and it sticks. |
| [Grid Garden](https://cssgridgarden.com/) | Same idea for CSS grid. |
| [Coolors](https://coolors.co/) | Generate a colour palette. Press space for a new one. Copy the hex codes into the CSS. |
| [Google Fonts](https://fonts.google.com/) | Free fonts. Pick one, copy the `<link>` tag into the `<head>`, set `font-family` in CSS. |
| [CSS Gradient](https://cssgradient.io/) | Build a gradient background by clicking, copy the CSS. |
| [Lucide](https://lucide.dev/icons/) | Clean SVG icons. Click one, copy the SVG, paste it into the HTML. No library needed. |

## JavaScript

| Site | What it is good for |
|---|---|
| [MDN: Array methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) | The quiz stores questions in an array. `push`, `filter`, `map`, `sort` and friends are all here. |
| [MDN: Document Object Model](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) | How JS finds and changes elements on the page. Start with `querySelector` and `textContent`. |
| [MDN: setInterval](https://developer.mozilla.org/en-US/docs/Web/API/Window/setInterval) | Run code every X milliseconds. Used in the click game, handy for a countdown in the quiz. |
| [MDN: localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) | Save a high score or a name so it survives a page refresh. Two lines of code. |
| [Math.random on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random) | Random numbers for positions, colours, shuffling questions. |
| [Eloquent JavaScript](https://eloquentjavascript.net/) | Free book. Chapters 1 to 4 cover everything the templates use. Chapters 13 to 15 are about the browser. |

## Try code in the browser

| Site | What it is good for |
|---|---|
| [CodePen](https://codepen.io/) | Paste HTML, CSS and JS in three boxes and see the result live. Great for testing one idea without breaking your file. |
| [JSFiddle](https://jsfiddle.net/) | Same idea as CodePen, a bit simpler. |
| [Browser DevTools](https://developer.chrome.com/docs/devtools/open) | Press F12 in the browser. The Console tab shows your errors. The Elements tab lets you click on anything and see its CSS. This is the most useful tool on this page. |

## Debugging

| Site | What it is good for |
|---|---|
| [MDN: What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/What_went_wrong) | Short guide to reading error messages and fixing the usual mistakes. |
| [Stack Overflow](https://stackoverflow.com/) | Someone had your problem before. Paste the exact error message from the console into the search bar. Read the accepted answer and one other. |
| [HTML validator](https://validator.w3.org/#validate_by_upload) | Upload your HTML file. Finds forgotten closing tags and typos in attributes. |

## Cheatsheets

| Site | What it is good for |
|---|---|
| [HTML cheatsheet](https://htmlcheatsheet.com/) | All tags on one page. |
| [CSS cheatsheet](https://htmlcheatsheet.com/css/) | All properties on one page, with live preview. |
| [JavaScript cheatsheet](https://htmlcheatsheet.com/js/) | The common syntax on one page. |
| [Keyboard shortcuts for VS Code](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf) | One-page PDF. Ctrl-D, Alt-Up and Ctrl-/ alone save you an hour. macOS version on the same site. |

## How to search

Three rules that make searching work.

1. Put the language first. `javascript shuffle array` beats `how do I make the questions random`.
2. Paste the exact error text from the console. Leave out your own variable names.
3. Prefer results from MDN, javascript.info, Stack Overflow and CSS-Tricks. Skip results that want you to install something.

## About AI

AI is allowed as a helpdesk during the hackathon, not as a generator. Good use: paste an error and ask what it means. Ask what a line of code does. Ask for the name of the CSS property that does X, then look it up on MDN. Bad use: asking for the whole feature and pasting it in. You learn nothing and you cannot fix it when it breaks.
