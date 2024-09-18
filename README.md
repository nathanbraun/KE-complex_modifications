# KE-complex_modifications

This repository add's [rcmdnk](https://rcmdnk.com/)'s vim_emu rules to
Karabiner-Elements.

## Changes
This is a fork of [https://github.com/rcmdnk/KE-complex_modifications](https://github.com/rcmdnk/KE-complex_modifications).

Differences:
- it enables vim_emu in the browser
- it *disables* vim_emu in the alacritty/kitty terminal

## Installation
Assuming you have [Karabiner-Elments](https://karabiner-elements.pqrs.org/)
installed:

1. Clone this repository.
2. `cd` into it
3. Copy the `vim_emu.json` file to Karabiner-Elements with:

```sh
$ cp ./docs/json/vim_emu.json ~/.config/karabiner/assets/complex_modifications
```

4. Open Karabiner-Elements and go to Complex Modifications >> *Add predefined
   rule*. You should see the vim_emu rules and can add what you want.

Note these instructions orignally came from [rcmdnk
here](https://github.com/rcmdnk/KE-complex_modifications/issues/4).  All credit
to rcmdnk for the great KE plugin!
