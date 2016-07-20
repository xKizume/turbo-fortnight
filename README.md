
Flash Stock + Unroot [WugFresh Development]
 ------------------------------------------------------------------


(bootloader) has-slot:bootloader: not found
target reported max download size of 536870912 bytes
sending 'bootloader' (10387 KB)...
OKAY [  0.370s]
writing 'bootloader'...
(bootloader) flashing partition ...
(bootloader) This may take a few seconds if a
(bootloader) different partition table is being
(bootloader) flashed since we need to backup
(bootloader) and restore a few partitions
(bootloader) Flashing primary GPT image...
(bootloader) Failed to write primary GPT.

(bootloader) Failed to flash partition
FAILED (remote failure)
finished. total time: 11.586s
rebooting into bootloader...
OKAY [  0.003s]
finished. total time: 0.003s

(bootloader) has-slot:radio: not found
target reported max download size of 536870912 bytes
sending 'radio' (115508 KB)...
OKAY [  3.824s]
writing 'radio'...
(bootloader) flashing modem ...
(bootloader) Failed to erase partition
(bootloader) Failed to flash modem
FAILED (remote failure)
finished. total time: 14.855s
rebooting into bootloader...
OKAY [  0.002s]
finished. total time: 0.003s

(bootloader) has-slot:boot: not found
target reported max download size of 536870912 bytes
sending 'boot' (8181 KB)...
OKAY [  0.262s]
writing 'boot'...
(bootloader) Failed to flash partition boot

(bootloader) Failed to flash partition boot
FAILED (remote failure)
finished. total time: 22.877s

(bootloader) has-slot:cache: not found
target reported max download size of 536870912 bytes
erasing 'cache'...
(bootloader) Failed to erase partition
FAILED (remote failure)
finished. total time: 5.791s

(bootloader) has-slot:recovery: not found
target reported max download size of 536870912 bytes
sending 'recovery' (8899 KB)...
OKAY [  0.285s]
writing 'recovery'...
(bootloader) Failed to erase partition
(bootloader) Failed to flash partition recovery
FAILED (remote failure)
finished. total time: 6.139s

(bootloader) has-slot:system: not found
target reported max download size of 536870912 bytes
sending sparse 'system' 1/4 (517177 KB)...
OKAY [ 17.512s]
writing 'system' 1/4...
(bootloader) Failed to erase partition
FAILED (remote failure)
finished. total time: 23.300s

Creating filesystem with parameters:
    Size: 28474998784
    Block size: 4096
    Blocks per group: 32768
    Inodes per group: 8160
    Inode size: 256
    Journal blocks: 32768
    Label:
    Blocks: 6951904
    Block groups: 213
    Reserved block group size: 1024
Created filesystem with 11/1738080 inodes and 153124/6951904 blocks
(bootloader) has-slot:userdata: not found
target reported max download size of 536870912 bytes
erasing 'userdata'...
(bootloader) Failed to erase partition
FAILED (remote failure)
finished. total time: 5.840s

Creating filesystem with parameters:
    Size: 268435456
    Block size: 4096
    Blocks per group: 32768
    Inodes per group: 8192
    Inode size: 256
    Journal blocks: 1024
    Label:
    Blocks: 65536
    Block groups: 2
    Reserved block group size: 15
Created filesystem with 11/16384 inodes and 2089/65536 blocks
(bootloader) has-slot:cache: not found
target reported max download size of 536870912 bytes
erasing 'cache'...
(bootloader) Failed to erase partition
FAILED (remote failure)
finished. total time: 5.792s

rebooting...

finished. total time: 0.003s
