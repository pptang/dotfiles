# ~/dotfiles

## Install `nix`

Follow the [manual](https://nixos.org/nix/manual/#sect-macos-installation):

```
$ sh <(curl -L https://nixos.org/nix/install) --darwin-use-unencrypted-nix-store-volume
```

## Install `Oh My Zsh`

Follow the [manual](https://github.com/ohmyzsh/ohmyzsh)

```
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Download terminal themes

Follow the [manual](https://github.com/lysyi3m/macos-terminal-themes).

Currently, I'm using `Flatland`

## How to set up

1. Clone this repo in your home directory
```
# ~/

git clone https://github.com/pptang/dotfiles.git
```

2. Install [GNU Stow](https://www.gnu.org/software/stow/)
```
brew install stow
```

3. Symlink dotfiles
```
cd ~/dotfiles
stow zsh # just an example, you can pass more
``` 


