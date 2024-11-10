# Automatic zram setup

I made this script since there are no init independent zram-related scripts and/or programs so I'll be making one for everyone to use

## Compatibility

It will run on any POSIX-Compliant shell, init system, coreutilities (Tested on chimerautils)

## Userspace Dependencies

A posix compliant environment, and util-linux (for `mkswap`, `swapon`, and `zramctl`).
