# rk322x-buildroot
External buildroot tree for rk322x board

## getting started

clone this repo and buildroot and then

```
$ cd build-root-extracted-dir
$ make BR2_EXTERNAL=/path/to/this/downloaded/repo rk322x_defconfig
$ make menuconfig # customize build
$ make # shopping time ^__^
```

flash generated image on sdcard and enjoy
