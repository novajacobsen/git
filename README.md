# git

git config for general use

## Installation

1: If you have a `~/.config/git/config` already move it to `~/.gitconfig`
2: If you haven't already set your user name and email with `git config --global user.email <EMAIL> && git config --global user.name <NAME>`
3: Clone this repo into `~/.config/git` with `git clone https://github.com/novajacobsen/git.git ~/.config/git`
4: You're now ready to use my aliases and other quality of life changes.

## How it works

The file `congig` should end up at path `~/.config/git/config` which is read as a global config by git.
Git loads `~/.gitconfig` after this file and newest value wins. So any settings set there will win over mine.

When both `~/.gitconfig` and `~/.config/git/config` exist `git config --global` will always set values to
`~/.gitconfig` so you can freely add your own configuration without it affecting this file.
