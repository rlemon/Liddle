#Notes:

	Please only add to this document, do not remove any suggestions. 
	Thanks,
		rlemon.


Suggested Commands
--------------------------------------------------------

######TAB
- insert tab character at caret position, move caret past the tab character.
- on a range; add a tab character to the beginning of each line in the range. If the range is a single line, add it to the beginning. Keep the range selected.

######SHIFT+TAB
- remove tab character at caret position, move caret into removed characters position.
- on a range; remove a tab character from the beginning of each line in the range. If the range is a single line, remove it at the beginning. Keep the range selected.

######CTRL+D
- clone current line and insert after said line, do not move caret.
- on a range; clone current range and append to itself. do not insert any new lines. do not unselect the range.

######ENTER
- new lines should take on the last indentation of the line previous it.
- possibly; if the previous line opens a new block ( '{', '[' ) indent one more line.

######ALT+C
- insert double forward slash at the beginning of the current line, no not move the carat.
- on a range; wrap the range in [space]/\*[space]\<range>[space]\*/[space]. do not unselect the range.

######ENTER
- new lines should take on the last indentation of the line previous it.
- possibly; if the previous line opens a new block ( '{', '[' ) indent one more line.

