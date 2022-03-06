# drop-to-vim.sh

[![Actions Status: test](https://github.com/sasaplus1/drop-to-vim.sh/workflows/test/badge.svg)](https://github.com/sasaplus1/drop-to-vim.sh/actions?query=workflow%3A"test")

send [drop command](https://vim-jp.org/vimdoc-en/terminal.html#terminal-api) to Vim from [Terminal mode](https://vim-jp.org/vimdoc-en/terminal.html)

## How to use

open file with Vim via terminal mode:

```console
$ drop-to-vim file1.txt file2.txt file3.txt
```

### via [Vifm](https://vifm.info/) within terminal mode

add to `vifmrc` the following:

```vim
if $VIM_TERMINAL
  set vicmd=drop-from-vifm
endif
```

## License

The MIT license.
