# TWRP Tree for Elite B55 [STAGING]

# IMPORTANT
```bash
THIS TREE ISN'T READY FOR PRODUCTION YET! IF YOU AREN'T GOING TO CONTRIBUTE AS YOU FIX BUGS, GO MAKE YOUR OWN TREE INSTEAD!
```

# Getting started
```bash
# Make folder
$ mkdir twrp ; cd twrp

# Clone TWRP tree
$ repo init -u https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-10.0

# Clone this repo
$ git clone https://github.com/windowzytch/recovery_device_sky_b55 -b omni-10.0 device/sky/b55

# Sync
$ repo sync

# Make some stuffs and build it
$ . build/envsetup.sh
$ lunch omni_b55-eng
$ make recoveryimage
```

------
©2021 Wind/owZ & Phoenix Bradley feat. あさぎりあや
