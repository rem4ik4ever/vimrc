# Vimrc configuration for WebDevelopment

This is Vimrc that I'm using for my day to day development with TypeScript and React.

## Requirements

- [Vim Plug](https://github.com/junegunn/vim-plug)
- Vim
- tons of patience while learning Vim

## Plugins used

- morhetz/gruvbox
- jremmen/vim-ripgrep
- tpope/vim-fugitive
- leafgarland/typescript-vim
- vim-utils/vim-man
- lyuts/vim-rtags
- kien/ctrlp.vim
- mbbill/undotree
- jaredgorski/spacecamp
- dense-analysis/ale
- neoclide/coc.nvim
- jiangmiao/auto-pairs
- prettier/vim-prettier
- alvan/vim-closetag

## Installation

- First install Vim Plug
- Copy and paste .vimrc into ~/.vimrc
- Run `vim ~/.vimrc` => `:source %` => `:PlugInstall`

Check coc.nvim (documentation)[https://github.com/neoclide/coc.nvim] for intellisense like in VS code
eg for typescript you will need to run `:CocInstall coc-tsserver`
