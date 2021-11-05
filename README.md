# th4tkh13m/onenord.nvim 
## (Based on shaunsingh/nord.nvim and rmehri01/onenord.nvim)

## Neovim theme based off of the [Nord Color Palette](https://www.nordtheme.com/docs/colors-and-palettes) and [Atom's OneDark Color Pallete](https://github.com/atom/atom/tree/master/packages/one-dark-ui)

![OneNord](https://user-images.githubusercontent.com/29520244/140460591-0eddc8ae-0e50-4e7c-858c-9b063d435574.png)

## Features

OneNord.nvim is a colorscheme written in lua for NeoVim that is inspired on [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) and [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim). It is meant to combine the best of these two colorscheme: The speed of nord.nvim and the readble of onenord.nvim


### Why does this repository exist? Don't we have [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) and [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim)?

That is a good point. I do love [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim), but the constrast of the colorscheme does not satisfy me! The comments are hard to see, as well as some elements as keywords and modifiers have the same colors. Otherwise, [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim) has the perfect colorscheme I need, but I do notice it makes my startuptime a little bit slower (10ms) than [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim).

### Supported plugins

- [TreeSitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [LSP Diagnostics](https://neovim.io/doc/user/lsp.html)
- [Lsp Saga](https://github.com/glepnir/lspsaga.nvim)
- [LSP Trouble](https://github.com/folke/lsp-trouble.nvim)
- [Git Gutter](https://github.com/airblade/vim-gitgutter)
- [git-messenger](https://github.com/rhysd/git-messenger.vim)
- [Git Signs](https://github.com/lewis6991/gitsigns.nvim)
- [Telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [Nvim-Tree.lua](https://github.com/kyazdani42/nvim-tree.lua)
- [NERDTree](https://github.com/preservim/nerdtree)
- [vim-which-key](https://github.com/liuchengxu/vim-which-key)
- [Indent-Blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [Dashboard](https://github.com/glepnir/dashboard-nvim)
- [BufferLine](https://github.com/akinsho/nvim-bufferline.lua)
- [Neogit](https://github.com/TimUntersberger/neogit)
- [vim-sneak](https://github.com/justinmk/vim-sneak)
- [lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim)

## Requirements

NeoVim >= 0.5.0

## Installation

```vim
" Via Vim-Plug
Plug 'th4tkh13m/onenord.nvim'
```

```lua
-- Via Packer
use 'th4tkh13m/onenord.nvim'
```

## Usage

Just enable the colorscheme in NeoVim

```vim
"Vim script"
colorscheme onenord
```

```lua
-- Lua
require'onenord'.set()
```


