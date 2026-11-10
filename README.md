# PicoStation Multi House art

Menu artwork for the PicoStation Multi House firmware, one pair of files per disc serial:

- `art/default/<SERIAL>-CASE.art`: case art
- `art/default/<SERIAL>-CD.art`: disc art

Each file is a 10,240 byte `.art` image (96x96, 256 color palette). The files come from the `database/art/default`
folder of the original PicoStation Multi House package by alberonisse.

The macOS port, [orenatobr/PicoStation-MultiHouse-macOS](https://github.com/orenatobr/PicoStation-MultiHouse-macOS),
downloads the files it needs from this repository when you add a game, so there is nothing to copy by hand.
To supply art for a new serial, open a pull request that adds both files under `art/default`.
Open an issue if you own a file here and want it removed.
