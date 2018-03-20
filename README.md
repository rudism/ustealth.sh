# ustealth.sh

Shell script to corrupt the MBR of a vWii usb drive to prevent the Wii U from nagging you to format it every time you boot up.

## Usage

### Corrupt the MBR

```
# ustealth hide /dev/sdX
```

### Fix the MBR

```
# ustealth unhide /dev/sdX
```

## Warning

Using this on the wrong device could seriously mess up your computer. Be very sure you know what you're doing. You'll probably need to run it as root. You'll probably also need to unhide it before you can use programs to manage the vWii WBFS partition and then re-hide it before plugging the drive back into your Wii U.

Special thanks to [gotem](https://gbatemp.net/threads/ustealth-wii-u-format-disk-nag-workaround.352786/page-12#post-4968191).
