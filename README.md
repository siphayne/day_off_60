# Day Off Vial Support

![Day Off](https://imgur.com/XAmF78B)

A 60% with a knob and a few macros. [More info at nixkeyboards.com](https://nixkeyboards.com/)

* Keyboard Maintainer: [Schrobie](https://github.com/schrobie)
* Some help with Vial: [siphayne](https://github.com/siphayne)
* Hardware Supported: Day Off PCBs, both solderable and hotswap
* Hardware Availability: [Nix Keyboards](https://nixkeyboards.com/)

#### Building the Vial Hex

Make example for this keyboard (after setting up your build environment):

1. Get vial-qmk here:
2. Copy this repo into vial-qmk/keyboards/\<this repo\>
3. `cd vial-qmk`
4. `qmk compile -kb <this repo> -km vial`
5. `qmk compile` will well you where the output hex goes
6. Flash the output hex
7. Great success!

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).


