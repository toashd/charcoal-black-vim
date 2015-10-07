Charcoal Black for Vim
==================

A lightweight black theme for Vim inspired by the prominent [Charcoal Black](http://gnuemacscolorthemetest.googlecode.com/svn/html/charcoal-black-c.html) Emacs
theme.

![alt screenshot](https://cloud.githubusercontent.com/assets/1436166/10335638/7f6ec6dc-6cf2-11e5-9229-631646de21c8.png)

Installation
------------

If you [use vim +
pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)

    cd ~/.vim
    git submodule add git@github.com:toashd/charcoal-black-vim.git bundle/charcoal-black-vim

if you [use vim + vundle](https://github.com/gmarik/vundle)

    " add to .vimrc
    Plugin 'toashd/charcoal-black-vim'
    :PluginInstall

or just copy all the files in `colors/*.vim` to
  `~/.vim/colors`

    # after downloading; unpacking; cd'ing
    cp colors/* ~/.vim/colors

License
------------------------
MIT
