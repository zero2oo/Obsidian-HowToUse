You can format code both inline within a sentence, or in its own block.

### Inline code 

You can format code within a sentence using single `backticks.`

If you want to put backticks in an inline code block, surround it with double backticks like so: ``code with a backtick ` inside``.

To format a block of code, surround the code with triple backticks:
```
cd ~/Desktop
```

You can also create a code block by indenting the text using `Tab` or 4 blank spaces:

	cd ~/Desktop

You can add syntax highlighting to a code block, by adding a language code after the first set of backticks.
```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

Obsidian uses Prism for syntax highlighting. For more information, refer to [Supported languages](https://prismjs.com/#supported-languages).

Note
[Source mode](https://help.obsidian.md/Editing+and+formatting/Edit+and+preview+Markdown#Source%20mode) and [Live Preview](https://help.obsidian.md/Editing+and+formatting/Edit+and+preview+Markdown#Live%20Preview) do not support PrismJS, and may render syntax highlighting differently.