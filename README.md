# amntr
simplifies mounting and umounting of disks from the shell

usage
---
devices that should not be touched by the script can be added to an ignore list in the script
devices that should be mounted at a fixed location can have their mount point and uuid specified
`amntr m # mounts all attached block devices to /mnt/n`
`amntr u # unmounts all attached block devices`
`amntr u -e # unmounts all attached block devices and powers them off (requires udiskctl)`

