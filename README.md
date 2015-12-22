VIM IDE for C Language
======================
This is my personal Vim environment setup. This package consist of minimum Vim plugins required for increasing productivity while working with C/C++ code.
Use this set of plugin to create environment similar to mine.


Plugins used
------------
Below is the list of plugins used for the creation of this plugin-set. This list will help you look at their documentation to use them more efficiently.

[pathogen](https://github.com/tpope/vim-pathogen)
----------
This is a Vim plugin manager. 
Their are various plugin manager for Vim and I tried few of them. However, I decided to stick with pathogen because this works in a simple and cleaner way. Compared to other plugin which either clutters the .vimrc file or have non defined way of working.


[NERD_tree](https://github.com/scrooloose/nerdtree)
-----------
This is file explorer plugin for Vim.

[minibufexpl](https://github.com/fholgado/minibufexpl.vim)
-------------
I found this plugin to be promising in terms that it shows each of the opened buffer. Further I like the way this plugin displays all buffers. It just opens the buffer in a new Vim window. This new window has all functionality of Vim (like searching). Further just pressing enter key over any file name will open buffer for that file.

[taglist](http://www.vim.org/scripts/script.php?script_id=273)
This plugin works with ctags (So make sure that ctags executable is already installed). This shows all available tags in the opened file. This plugin provides an interesting feature to browse the C file using function and variable tags.

[ctrl-p](https://github.com/ctrlpvim/ctrlp.vim)
This is a function/file/buffer search utility. For example this can search for matching filename in current folder and all its sub folder. We can open this searched file by pressing enter key over searched file.

[YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
---------------
This is one of the awesome plugin to work with. This plugin is a bunch of package bundled together, used for auto-completion. Required Linux package to use these plugin: build-essential, cmake and python-dev for this to work.

[NERD Commenter](https://github.com/scrooloose/nerdcommenter) 
NERD Commenter plugin provides enhanced commenting facility for various languages. Some example includes:
1) Comment/Uncomment 1 line
2) Comment/Uncomment multiple line
3) Comment/Uncomment visually selected area
4) Toggle commenting in all selected lines
# This plugin describes all functionality with respect to <leader> key. Default leader key is '\'. So, 
[count]<leader>cc |NERDComComment|
is equivalent to:
\cc

[Conque shell](http://www.vim.org/scripts/script.php?script_id=2771)
This plugin is used to embed terminal inside Vim. This is one of the required feature so that we do not have to go to the bash prompt for doing these operations. 

[vim-airline](https://github.com/bling/vim-airline)
Every one requires a good ecosystem to work. This plugin is used to provide a colorful ecosystem in Vim. This adds informative, colorful top and status bar.
# By default in terminal mode max color set to use is 8, To view the beauty of this plugin one should change the number of colors terminal can use.So: `set t_Co=256` for displaying colors.
Further I installed power-line fonts to make this plugin even more beautiful.
[ultimate.vim](https://amix.dk/vim/vimrc.html)
This is not any standard plugin, however this is the set of standard settings for Vim.
