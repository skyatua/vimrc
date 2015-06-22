set nocompatible

set tabstop=4
set shiftwidth=4
set smarttab
set noexpandtab
set wrap
set ai
set cin
set showmatch
set hlsearch
set incsearch
set ignorecase
set ffs=unix,dos,mac
set fencs=utf-8,cp1251,koi8-r,ucs-2,cp866

set number
set paste

execute pathogen#infect()
syntax on
filetype plugin indent on

colorscheme spring
set wildmode=longest:list,full

" nnoremap <F5> :make!<cr>
" nnoremap <F2> :vertical wincmd f<CR>

let g:ycm_global_ycm_extra_conf = "~/.vim/.ycm_extra_conf.py"

set exrc
set secure
