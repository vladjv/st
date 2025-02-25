## vladjv'sbuild of st

## Usage
Get more information about the usage of my build, including useful keybindings
by executing `man st` in your terminal.

## Used patches from suckless project
- scrollback + mouse:       Add scrollback funcionality

## Apply patches to include features
- `patch -p1 -u -i patches/...`

## Installation 
- `git clone https://github.com/vladjv/st.git`
- `cd st`
- `make`
- `sudo make install`

## Future steps
All the code can be expanded from source. Also, to change some of the configurations
you need edit the "config.h", do not edit "config.def.h".
