## Brew
[Homepage](http://brew.sh/)

Install via ruby:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Other Base Stuff

* GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed, `sed`
  ```bash
  brew install coreutils moreutils findutils
  ```

## Brew Cask Installation
A nice way of installing GUI packages, along with [updating them](https://github.com/buo/homebrew-cask-upgrade).

```bash
brew install caskroom/cask/brew-cask
brew tap caskroom/versions
brew tap caskroom/fonts
```

To Update Brew and Casks:

```bash
brew update
brew doctor
brew cleanup
brew prune
```
