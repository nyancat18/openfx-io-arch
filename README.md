# OpenFX module

This is a VFX pack for Natron

Table of Contents
* [Download](#download)
* [Building](#building)
    * [OptDeps](#OptDeps)
    * [Build flags](#build-flags)
* [Credits](#credits)
* [License](#license)
* [Donations](#donations)



## Download
* **Arch Linux**:
Pre-built binaries are hosted in the AUR: [OpenFX](https://aur.archlinux.org/packages/openfx-io/)

## Building

*The build process takes about ½ hour on a shitty pc and 10 min with a good hardware, i5-3550 CPU @ 3.90GHz and 16GB ram. (without ccache)*



### OptDeps

##### firejail-extras
Lets you run Natron at an isolated, network-less enviorment, without run an expensive VM.

##### natron-plugins
A set of python plugins

##### natron-openfx-gmic-bin
Lets you use the GMIC API at Natron

### Build flags
make CONFIG=release

## Credits
* [OpenFX](https://github.com/MrKepzie/openfx-io)


## License
GPLv3. See [LICENSE](LICENSE)

## Donations
Donations are welcome and keep me motivated :-)
* BTC: `1JUhp2T15jPM9Y5r3uWmiyzMbAaRMNdoQg`
* LTC: `LfDZfSaoyGtm8nEmfE4tsz8MtajPXfDAYd`
