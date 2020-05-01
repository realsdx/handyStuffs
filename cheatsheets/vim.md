# Vim Cheatsheet

### Save files in Vim
    :wq - (save and quit)
    :w  - (Save the current file)
    :w <name> - Save the current copy under new name but edits the original file
    :sav <name> - Save the current copy under new name and edits the new file  
    :q! - (quit vim without saving)  

    Shift+zz - (Save and quit)



### Navigation
    * General Movement
    j - Move one line down
    k - Move one line up
    h - Move one char left
    l - Move one char right
    5k - Move 5 lines up
    5j - Move 5 lines down


    
    
    * Page movement
    gg - Go to first line
    G - Go to last line
    :10 - Go to line 10

    * Word movement
    w - Move to next word (cursor at the start of word)
    b - Move to previous word (cursor at the start of word)
    e - Move to next word (cursor at the end of word)

    * Miscellaneous
    $ - Go to end of the current line

    
### Edits
    d - cut selected text
    dd - cut current line
    x - delete selected text

    p - paste text

    y - copy/yank selected text
    yy - copy current line
    yyp - duplicate current line to downward

### Modes in Vim
    i - Insert mode
    : - command mode
    <esc> - Return to normal mode
    R - Replace mode


