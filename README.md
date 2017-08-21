# My bootstrap script


```
# for macOS
## Install git
sudo xcodebuild -license

## Install homebrew
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update

## Install Ansble
brew install ansible

# for Ubuntu
$ TBD

# Clone repository
$ git clone git@github.com:rmanzoku/ansible-mybootstrap.git "$HOME/.ansible-mybootstrap"

# Run
$ cd $HOME/.ansible-mybootstrap
$ ansible-playbook bootstrap.yml
```
