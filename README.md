android_img_repack_tools
========================

> android_img_repack_tools is a kit of utilities for unpacking/repacking android ext4 and boot images

#### This branch allows compiling on Mac OSX.


## Requirements:

* Install [Homebrew](http://brew.sh/)
* Install GNU sed: `brew install gnu-sed`
* Install GCC 4.9: `brew install homebrew/versions/gcc49`

## Compiling:

1. use `./configure` to download source from android git repositories

2. use `make` to compile the following binaries:
	* `mkbootfs`
	* `simg2simg`
	* `make_ext4fs`
	* `mkbootimg`
	* `sgs4ext4fs`
	* `unpackbootimg`
	* `ext2simg`
	* `img2simg`
	* `simg2img`

--------------------------------------------------------------------------------

* `make clean` will clean sources
* `make clear` will remove sources
