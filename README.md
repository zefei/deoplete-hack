# deoplete-hack

[deoplete](https://github.com/Shougo/deoplete.nvim) source for 
[Hack](http://hacklang.org/).

## Install

You need to have [Hack 
setup](https://docs.hhvm.com/hack/getting-started/getting-started) before you 
can use it inside Vim.

Use your favorite plugin manager and add `zefei/deoplete-hack` to your `.vimrc`:

    Plug 'zefei/deoplete-hack'
    # or
    Plugin 'zefei/deoplete-hack'
    # or
    NeoBundle 'zefei/deoplete-hack'

## Options

* `g:deoplete#sources#hack#hh_client` (default `'hh_client'`): path to 
  `hh_client`.
* `g:deoplete#sources#hack#timeout` (default `0.5`): timeout (in seconds) for 
  `hh_client` response.
