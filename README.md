# Online JS Code Console

### [Try it out](https://darrowv.github.io/JsLogs/)

## Features
- Syntax highlighting
- Dark and light themes
- Some "CodeMirror" features as brackets closing, match highlighting etc.
- Minimalistic design, just your js code input and console output
- The code is saved in localstorage when the run button is pressed and is overwritten with each subsequent press.

## Tips
- You can also use the keyboard shortcuts to run the code (Ctrl+Enter) and to clear console output (Ctrl + \\)
- You can change the theme of the editor by clicking on (initially) the moon.

## Code Snippets
There are some code snippets added in code editor for convenience. If you want some more, let me know about it. Here is the list of current snippets:

```javascript
var customSnippets = {
  "cl": 'console.log();',
  "cc": "console.clear();",
  "fd": "function name() {\n\n};",
  "af": "let foo = () => {};",
  "lorem": `"Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis ab eveniet ipsa hic quod, ipsam quia quo? Nam consequatur, nostrum ullam consequuntur mollitia ipsa deserunt eaque, ipsam quo sit animi!"`
}
```

To activate code snippet just type it and press Tab.

## Contribution
We welcome contributions from the community to improve the editor. You can fork the repository and create a pull request with your changes.

## Credits
- The code editor is made using the [CodeMirror library](https://codemirror.net/). Guided by [this manual](https://www.math.ucla.edu/sites/all/libraries/codemirror/doc/manual.html).
- Favicon taken from [svgrepo](https://www.svgrepo.com/svg/427431/brochure-document-menu).
- The idea of theme switching mechanism is taken from [here](https://dev.to/vaishnavs/simple-dark-light-toggle-with-vanillajs-2cbj).
- The script for resizing divs by dragging was taken from [here](https://htmldom.dev/).

## Licensing
This software is released under the [MIT License](https://opensource.org/licenses/MIT).

Thanks for using this app! Happy coding!
