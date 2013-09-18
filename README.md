vim-config
==========

Configuration for vim

# Installation
1. Install Vim Pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle; \
curl -Sso ~/.vim/autoload/pathogen.vim \
    https://raw.github.com/tpope/vim-pathogen/master/autoload/pathogen.vim
```

2. Clone this repo and init submodules
```
git clone https://github.com/phoorichet/vim-config.git
cd vim-config
git submodule init
git submodule update
```

3. Copy .vimrc to your .vimrc
```
cd vim-config
cp .vimrc ~/.vimrc
```

4. Copy submodule to you vim bundle

In vim-config directory:
```
cp -r .vim/bundle/* ~/.vim/bundle/
```

# List of plugins
1. vim/bundle/ctrlp.vim
2. vim/bundle/emmet-vim
3. vim/bundle/syntastic
4. vim/bundle/vim-bundler
5. vim/bundle/vim-endwise
6. vim/bundle/vim-fugitive
7. vim/bundle/vim-gitgutter
8. vim/bundle/vim-indent-guides
9. vim/bundle/vim-jsbeautify
10. vim/bundle/vim-powerline
11. vim/bundle/vim-rails
12. vim/bundle/vim-sensible


