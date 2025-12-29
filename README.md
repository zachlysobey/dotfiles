# Zach's dotfiles

## Some random notes

### Homebrew

I use homebrew to install some stuff.

> https://brew.sh/

#### a sample of stuff I install with brew:

-   `brew install nvm`
    - *maybe not best with brew anymore*
-   `brew install tree`
-   `brew install thefuck`

### Aliasing stuff to the home directory

Examples:

```sh
# from this repo
DOTFILES=$(pwd)
ln -s $DOTFILES/.npmrc ~/.npmrc
ln -s $DOTFILES/.gitconfig ~/.gitconfig
```

### `oh-my-zsh`

I use `zsh` with `oh-my-zsh` instead of bash

> https://ohmyz.sh/

#### .zshrc config

I usually just `source` the relevant files from this repo in my `~/.zshrc`.

### VSCode setup


#### The `code` command

https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line

#### other settings

I have `vscode/settings.json` here, but its kinda specific to AP stuff. I'm keeping it for reference for now.
