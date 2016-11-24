# Vim commands to remember 

- ctrl-c - Quit insert mode (similar to esc) 
- ctrl-e - Scroll viewport down
- ctrl-y - Scroll viewport up 

### Paste without auto-indents
:set paste
<PASTE>
:set nopaste

### Paste 0-9 previous yanks

See registered yanks:
:reg

Paste by number:
""p (latest yank)
"0p (2nd latest yank)
... so forth until 9

See [example usage here](http://superuser.com/questions/102815/vim-cut-and-paste-history)

## Resources

- [php.vim syntax highlighting sheet](https://github.com/StanAngeloff/php.vim/blob/48fc7311fa07c2b83888e7a31fae03118bae720b/syntax/php.vim#L754)
- [vim-php-namespace](https://github.com/arnaud-lb/vim-php-namespace)
- [Leader binding and Tmux the right way](http://sheerun.net/2014/03/21/how-to-boost-your-vim-productivity/)
- [Vim + tmux 1h YouTube-video, great intro](https://www.youtube.com/watch?v=5r6yzFEXajQ)
