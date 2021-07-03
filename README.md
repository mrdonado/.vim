# .vim folder

In order to use this configuration, follow these steps:

- Clone this repository in your `~/.vim` directory.
- Copy the file `./vimrc` of this repository to your home directory as `~/.vimrc` or create a symbolic link (e.g.: `sh ./setup-symlinks.sh`)
- Open vim and run `:PluginInstall` in normal mode

## Install oh-my-zsh plugins

```sh
brew install zsh-syntax-highlighting
```

## Install powerlevel9k (maybe)

```sh
brew tap sambadevi/powerlevel9k
brew install powerlevel9k
```

To load powerlevel9k in your zsh simply add the following line to your .zshrc:

`source /usr/local/opt/powerlevel9k/powerlevel9k.zsh-theme`

