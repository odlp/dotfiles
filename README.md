# Dotfiles

```sh
git clone https://github.com/odlp/dotfiles.git ~/.dotfiles
~/.dotfiles/scripts/bootstrap
```

## Homebrew

```sh
brew tap Homebrew/bundle
brew bundle --file=~/.dotfiles/Brewfile
```

Updating Brewfile:

```
brew bundle dump -f --file=~/.dotfiles/Brewfile
```
