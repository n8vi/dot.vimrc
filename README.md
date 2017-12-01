## My (fairly simple) .vimrc

### set paste

Ensure pasted text doesn't get auto-indented.  Autoindent can go to hell and die, use `TAB` and `>>`/`<<`.

### set mouse=

Don't interpret mouse activity.  This allows copying from a terminal into X's clipboard, so you can actually paste into a different program.

### syntax on

Syntax highlighting helps, when designed correctly (ie, not dark, dark blue).

### set expandtab

When using `>>`, `<<`, and `TAB`, don't actually insert TABs into the file - use spaces instead.  If you want a real tab, say, if you're editing makefiles, use ctrl+v,tab.

### set shiftwidth=4

Four spaces, because python.

### set softtabstop=4

This is good too, I guess.


## Bonus: PRU Assembler (PASM) syntax hilighting files 
... in directories `ftdetect` and `syntax`.  Copy those dirs to 
~/.vim or their contents to their counterparts in /usr/share/vim/vim80.
