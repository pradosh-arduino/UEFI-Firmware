# UEFI-Firmware
this firmware is needed by the qemu to run UEFI based OSes  
# Setup
add these lines in qemu:

`-drive if=pflash,format=raw,unit=0,file=/path/for/UEFI/CODE,readonly=on -drive if=pflash,format=raw,unit=1,file=/path/for/UEFI/VARS`
