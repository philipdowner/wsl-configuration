# wsl-configuration
Helpers and configuration values for WSL2. Prefers PHPStorm/IntelliJ, git, and other dev tools.

I may turn this into [a .dotfiles project](https://github.com/philipdowner/dotfiles) eventually, but for now this repo is just a way to document and share my WSL settings. 

### Brew
The `brew/.Brewfile` is an output of my currently installed tools. Generate it using:
```shell
brew bundle dump --global
```

### Git

The `git/.gitconfig` file should be placed in your WSL user's home dir.

### Shell

The `shell/.profile` file should be placed in your WSL user's home dir.