# About
This repository stores my configuration files for Unix-like systems.

# Installation and Usage

**Quick Start**: in wherever you keep your repos (mine is at `~/software/`),
run the following command:

```sh
git clone --recursive https://github.com/mt-env/dotfiles && cd dotfiles && ./install.sh
```

These dotfiles are set up such that it should be possible to simply copy the
entire repo into `~/.config/` without any worries. The install script
specifically should be agnostic to where you cloned the repo, and hopefully
should work no matter where it's run from. If you're on the newest versions of
all the software, these dotfiles should work. If you're on older versions, it
may not. Open an issue if anything breaks!
