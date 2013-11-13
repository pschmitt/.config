This is a meta repo holding all my config file

## Installation

```
git clone --recursive https://github.com/pschmitt/.config.git ~/.config
```

This may fail if you already have a `.config` folder.

## Updating

```
cd ~/.config
git pull                                
git submodule update --init --recursive
git submodule foreach --recursive "git fetch" 
```

## Get ready to contribute 

This will checkout the `master` branch for each submodule and update them.

```
cd ~/.config
git pull
git submodule update --init --recursive
git submodule foreach --recursive "git checkout master; git pull"
```
