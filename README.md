
# Awesome Cheat Sheets [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


> Awesome Cheat Sheets for **Developer Utility**, like [Git](#git), [Vim](#vim)
, [Tmux](#tmux), [SublimeText](#sublimetext), [Markdown](#markdown), [Shell](#shell).

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

**Check out my [blog](http://mintisan.github.io) 🦄 or say *hi* on [Twitter](https://twitter.com/mintisan).**

## Table of Contents

- [Git](#git)
- [Vim](#vim)
- [Tmux](#tmux)
- [Sublime Text](#sublime-text)
  - [Sublime Regular Expressions](#sublime-regular-expressions)
- [Markdown](#markdown)
- [Shell](#shell)
- [Python](#python)

## [Git](https://git-scm.com/)

- [Git Cheet Sheet from git - the simple guide](http://rogerdudler.github.io/git-guide/) : [[PDF Download]](http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)

![](./attach/git_cheat_sheet.jpg)

- [Tower Git Cheat Sheet by Tobias Günther](http://www.git-tower.com/blog/git-cheat-sheet/) : [[PDF Download]](http://www.git-tower.com/blog/posts/git-cheat-sheet/git-cheat-sheet.zip)

![](./attach/git-cheat-sheet-large01.png)


- [Git CheetSheet from an interaction from NDP Software by Andrew Peterson](http://www.ndpsoftware.com/git-cheatsheet.html)

![](./attach/GitCheatsheetNDPSoftware.png)

- [Git cheat sheet, take two by Jan Krüger](https://jan-krueger.net/git-cheat-sheet-take-two/) : [[PDF Download]](https://jan-krueger.net/wordpress/wp-content/uploads/2007/09/git-cheat-sheet.pdf)

![](./attach/git-cheat-sheet.png)

- [git-flow cheatsheet created by Daniel Kummer](http://danielkummer.github.io/git-flow-cheatsheet/) : A cheatsheet on the usage of git flow

![](./attach/git_flow_cheatsheet.png)

- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet) : A collection of cool hidden and not so hidden features of Git and GitHub.

- [Git Cheat Sheet - git-flow](https://github.com/arslanbilal/git-cheat-sheet) : Git cheat sheet saves you from learning all the commands by heart.

## [Vim](http://www.vim.org/)

- [Graphical vi-vim Cheat Sheet](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html) : [[PDF Download]](http://www.glump.net/files/2012/08/vi-vim-cheat-sheet-and-tutorial.pdf)

![](./attach/vi-vim-cheat-sheet.png)

- [Vim Cheat Sheet from michael](http://michael.peopleofhonoronly.com/vim/) : [[PDF Download]](http://michael.peopleofhonoronly.com/vim/vim_cheat_sheet_for_programmers_screen.pdf)

![](./attach/vim_cheat_sheet_for_programmers_print.png)

- [Vim Cheat Sheet by Richard](http://vim.rtorr.com/)

![](./attach/Vim_Cheat_Sheet_by_Richard.png)

- [Vim Visual Cheat Sheet](http://blog.vgod.tw/2009/12/08/vim-cheat-sheet-for-programmers/) : [[PDF Download]](http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.pdf)

![](./attach/vim-cheat-sheet-en.png)

## [Sublime Text](http://www.sublimetext.com/)

- [Sublime Text Keyboard Shortcut Cheat Sheet by Chris Simpkins](http://sweetme.at/2013/08/08/sublime-text-keyboard-shortcuts/)

![](./attach/Sublime_Text_Keyboard_Shortcut_Cheat_Sheet_Sweetmeat.png)

- [ Sublime Text Periodic table of the Keyboard Shortcuts by WAKAMSHA](http://wakamsha.github.io/dev.cm/appendix/cheatsheet/sublimetext.html)

![PC](./attach/Sublime_Text_Periodic_table_of_the_Keyboard_Shortcuts_for_PC.png)

![Mac](./attach/Sublime_Text_Periodic_table_of_the_Keyboard_Shortcuts_for_Mac_OSX.png)

- [Sublime Text 2 Keyboard Shortcuts by Kyle Cearley](http://www.ractoon.com/2012/10/sublime-text-2-keyboard-shortcuts-printable/) : [[PDF Download for PC]](https://d38dico4iqn2di.cloudfront.net/wp-content/uploads/2012/10/sublime_text_2_shortcuts_printable_ractoon.pdf) [[PDF Download for Mac]](https://d38dico4iqn2di.cloudfront.net/wp-content/uploads/2012/10/sublime_text_2_shortcuts_mac_printable_ractoon.pdf)

![PC](./attach/sublime_text_2_shortcuts_for_pc.png)

![Mac](./attach/sublime_text_2_shortcuts_for_mac.png)

### [Sublime Regular Expressions]

A regular expression specifies a set of strings that matches it. This cheat sheet is based off Python 3's Regular Expressions (http://docs.python.org/3/library/re.html) but is designed for searches within Sublime Text.

```
Special Characters

	\			Escapes special characters or signals a special sequence.
	.			Matches any single character except a newline.
	^			Matches the start of the string.
	$			Matches the end of the string.
	*			Greedily matches 0 or more repetitions of the preceding RE.
	*?			Matches 0 or more repetitions of the preceding RE.
	+			Greedily matches 1 or more repetitions of the preceding RE.
	+?			Matches 1 or more repetitions of the preceding RE.
	?			Greedily matches 0 or 1 repetitions of the preceding RE.
	??			Matches 0 or 1 repetitions of the preceding RE.
	A|B			Matches A, if A is unmatched then matches B, where A and B are arbitrary REs.
	{m}			Matches exactly m many repetitions of the previous RE.
	{m,n}			Greedily matches from m many to n many repetitions of the previous RE.
	{m,n}?			Matches m many to n many repetitions of the previous RE.
```

```
[...]			Indicates a set of characters to match.

	[amk]			Matches 'a', 'm', or 'k'.
	[a-z]			Matches 'a' through 'z'.
	[a-f0-7]		Matches 'a' through 'f' or '0' through '7'.
	[a\-z]			Matches 'a', '-', or 'z'.
	[a-]			Matches 'a' or '-'.
	[-a]			Matches 'a' or '-'.
	[(+*)]			Matches '(', '+', '*', or ')'. [] matches special characters literally.
	[\w]			Matches the character class for '\w'. See character classes.
	[^5]			Matches anything other than '5'. '^' forms the complementary set only as the first character in a set.
	[]()]			Matches ']', '(', and ')'. ']' is taken literally only as the first character in a set.
	[()\]]			Matches ']', '(', and ')'.
```

```
(...)			Matches the RE inside the parenthesis and assigns a new group.
(?P<name>...)		The RE matched is accessible by the group indicated by name.

	(?...)			Extension notation which changes a RE's behavior. These do not assign a new group.
	(?aiLmsux)		Sets the corresponding flag to each letter. Does not work within Sublime Text.
	(?:...)			A non-capturing version of parenthesis. The matched substring cannot be retrieved later.
	(?P=name)		Matches the substring matched by the group named name.
	(?#...)			A comment, the contents are ignored.
	(?=...)			Lookahead assertion, the preceding RE only matches if this matches.
	(?!...)			Negative lookahead assertion, the preceding RE only matches if this doesn't match.
	(?<=...)		Positive lookbehind assertion, the following RE will only match if preceded with this fixed length RE.
	(?<!...)		Negative lookbehind assertion, the following RE will only match if not preceded with this fixed length RE.
	(?(id)true|false)	If group id exists then uses the true RE, else use the false RE.
```

```
Character classes
	\1			Matches the contents of the group labelled by the same number. Acceptable numbers are 1-99.
	\A			Matches at the start of the current string.
	\b			Matches the empty string at the beginning or end of a word. \b matches the boundary between \w and \W.
	\B			Matches the empty string not at the beginning or end of a word.
	\d			Matches any Unicode decimal digit, including 0-9.
	\D			Matches any Unicode non-decimal digit.
	\s			Matches any Unicode whitespace character, including ' ', \t, \n, \r, \f and \v.
	\S			Matches any Unicode non-whitespace character.
	\w			Matches any Unicode word character, including a-z, A-Z, and 0-9.
	\W			Matches any Unicode non-word character.
	\Z			Matches at the end of the string.

	\a			Matches the ASCII Bell ( ).
	\f			Matches the ASCII Formfeed ().
	\n			Matches the ASCII Linefeed.
	\r			Matches the ASCII Carriage Return ().
	\t			Matches the ASCII Horizontal Tab.
	\v			Matches the ASCII Vertical Tab ( ).
```

## [Tmux](https://tmux.github.io/)

- [tmux shortcuts & cheatsheet by Mohamed A. Hassan](https://gist.github.com/MohamedAlaa/2961058)

<script src="https://gist.github.com/MohamedAlaa/2961058.js"></script>

- [tmux cheat sheet by Andrey Tarantsov](https://gist.github.com/andreyvit/2921703)

<script src="https://gist.github.com/andreyvit/2921703.js"></script>

- [Tmux Quick Reference & Cheat sheet by Allen Fair](https://gist.github.com/afair/3489752)
<script src="https://gist.github.com/afair/3489752.js"></script>

![](./attach/tmux-quick-reference-and-cheat-cheet.png)

- [A tmux cheat sheet By Alvin Alexander](http://alvinalexander.com/linux-unix/tmux-cheat-sheet-commands-pdf) : [[PDF Download]](http://alvinalexander.com/downloads/linux/tmux-cheat-sheet.pdf)

![](./attach/tmux-cheat-sheet.png)

## [Markdown](https://daringfireball.net/projects/markdown/)

- [Markdown Cheatsheet from markdown-here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- [Markdown Cheatsheet by Jon Schlinkert](https://gist.github.com/jonschlinkert/5854601)
<script src="https://gist.github.com/jonschlinkert/5854601.js"></script>

- [Markdown Syntax Cheat Sheet by Station in the Metro](http://stationinthemetro.com/apps-and-scripts/markdown-cheat-sheet) : [[PDF Download]](http://stationinthemetro.com/wp-content/uploads/2013/04/Markdown_Cheat_Sheet_v1-1.pdf)

![](./attach/Markdown_Cheat_Sheet_v1-1_0001.jpg)

![](./attach/Markdown_Cheat_Sheet_v1-1_0002.jpg)

- [markdown cheat sheet by Scott](http://scottboms.com/downloads/documentation/markdown_cheatsheet.pdf) : [[PDF Download]](http://scottboms.com/downloads/documentation/markdown_cheatsheet.pdf)

![](./attach/markdown_cheatsheet.jpg)


## Shell

- [tldr](https://github.com/tldr-pages/tldr) : tldr is a collection of simplified and community-driven man pages.

![](./attach/shell-tldr-tar.png)

- [Linux Tutorial - Cheat SheetTutorial Sections ](http://ryanstutorials.net/linuxtutorial/cheatsheet.php)

![](./attach/shell-Linux-Tutorial-Cheat-Sheet.png)

- [Linux Tutorial - Grep Cheat Sheet](http://ryanstutorials.net/linuxtutorial/cheatsheetgrep.php)

![](./attach/shell-Linux-Tutorial-Grep-Cheat-Sheet.png)

- [Bash Redirections Cheat Sheet](http://www.catonmat.net/download/bash-redirections-cheat-sheet.pdf) : [[PDF Download]](http://www.catonmat.net/download/bash-redirections-cheat-sheet.pdf)

![](./attach/bash-redirections-cheat-sheet.jpg)

- [UNIX / LINUX CHEAT SHEET](http://cheatsheetworld.com/programming/unix-linux-cheat-sheet/)

![](./attach/Unix_Linux_Cheat_Sheet.png)

- [Linux Bash Shell Cheat Sheet](http://cli.learncodethehardway.org/bash_cheat_sheet.pdf) : [[PDF Download]](http://cli.learncodethehardway.org/bash_cheat_sheet.pdf)

![](./attach/bash_cheat_sheet.png)

- [Shell Scripting Cheat Sheet by Steve Parker](http://steve-parker.org/sh/cheatsheet.pdf) : [[PDF Download]](http://steve-parker.org/sh/cheatsheet.pdf)

![](./attach/simple_bash_cheatsheet.jpg)

- [Bash CheatSheet for Mac OSX by J. Le Coupanec](https://gist.github.com/LeCoupa/122b12050f5fb267e75f) : A little overlook of the Bash basics
<script src="https://gist.github.com/LeCoupa/122b12050f5fb267e75f.js"></script>

- [Terminal Mac Cheatsheet](https://github.com/0nn0/terminal-mac-cheatsheet)

- [GREP Cheat Sheet by Erica Gamet](http://www.ericagamet.com/wp-content/uploads/2011/11/Erica-Gamets-GREP-Cheat-Sheet.pdf) : [[PDF Download]](http://www.ericagamet.com/wp-content/uploads/2011/11/Erica-Gamets-GREP-Cheat-Sheet.pdf)

## Python

- [NumPy for MATLAB users](http://mathesaurus.sourceforge.net/matlab-numpy.html)
- [Numpy for Matlab users](https://docs.scipy.org/doc/numpy-dev/user/numpy-for-matlab-users.html)
- [Python & Pylab Cheat Sheet](http://www.physik.uzh.ch/lectures/informatik/python/res/pyrefcard.pdf)


## Complement

- [OverAPI.com](http://overapi.com/) : Collecting All Cheat Sheets
- [shortcutFoo](https://www.shortcutfoo.com/) : [shortcutFoo](https://twitter.com/#!/shortcutfoo) was created by programmers for programmers in an attempt to make learning your editor fun, easy, and effective. Akin to the days of first learning how to type on a keyboard, shortcutFoo aims to help programmers accomplish more in less time and with fewer keystrokes.
- [Cheatography](http://www.cheatography.com/) : Cheatography is a cheat sheet builder and repository where you can build, upload and share cheat sheets and quick references.
- [ShortcutWorld.com](http://www.shortcutworld.com/) : ShortcutWorld.com is an open, wiki-style Reference Database for Keyboard Shortcuts.
- [Cheat-Sheets.org](http://www.cheat-sheets.org/) : All cheat sheets, round-ups, quick reference cards, quick reference guides and quick reference sheets in one page. 
- [CheatSheet App for Mac OS X](https://www.mediaatelier.com/CheatSheet/) : Just hold the ⌘-Key a bit longer to get a list of all active short cuts of the current application. It's as simple as that.



## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Awesome Cheat Sheets</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://mintisan.github.io/" property="cc:attributionName" rel="cc:attributionURL">Ted Lin</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/mintisan/awesome-cheat-sheets" rel="dct:source">https://github.com/mintisan/awesome-cheat-sheets</a>.
