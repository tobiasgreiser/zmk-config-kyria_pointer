# Edit firmware

Go to https://nickcoutsos.github.io/keymap-editor/

# Flashing to nice!nano

Double tap reset button, execute

sudo mount /dev/sdb /mnt/stick

and copy file to /media/user/NICENANO with

sudo cp new_firmware.uf2 /mnt/stick/CURRENT.UF2

Wait until flashing is complete and unmount with

sudo umount /mnt/stick
