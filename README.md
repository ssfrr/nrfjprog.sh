nrfprog.sh
==========

This is a loose shell port of the nrfjprog.exe program distributed by Nordic,
which relies on JLinkExe to interface with the JLink hardware.

usage:

```
nrfjprog.sh <action> [hexfile]
```

where action is one of:
 * `--reset`
 * `--pin-reset`
 * `--erase-all`
 * `--flash`
 * `--flash-softdevice`
