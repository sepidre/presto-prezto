# presto-prezto

> Inspired by and based on [gh-zsh](https://github.com/gustavohellwig/gh-zsh) repository

A simple one-shot script to setup an awesome shell environment for Ubuntu and MacOS, with:
* prezto (https://github.com/sorin-ionescu/prezto)
* clvv/fasd (https://github.com/clvv/fasd)
* junegunn/fzf (https://github.com/junegunn/fzf)
* Peltoche/lsd (https://github.com/Peltoche/lsd)
* powerlevel10k theme (https://github.com/romkatv/powerlevel10k)

## Demo

After the installation is complete, the command prompt will look like this:
![ZSH-Prompt](./presto-prezto-example.png)
## Installation

``` bash
curl -fsSL https://raw.githubusercontent.com/JGroxz/presto-prezto/main/presto-prezto.sh | bash
```

## Notes
* If you are already using zsh, your zsh config will be backed up to .zshrc-backup-date.
* If the text/icons look broken, make sure your terminal is using one of the Nerd fonts.
* Tested on:
  * Ubuntu 20.04
  * MacOS 10.14, and 11.3
