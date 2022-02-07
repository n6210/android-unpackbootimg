Overtaken from

unpackbootimg

-i|--input boot.img
[ -o|--output output_directory]
[ -p|--pagesize ]

example:
    ./unpackbootimg -i boot.img  -o boot

---------------------------------------------------------------
mkbootimg

--kernel
--ramdisk
[ --second ]
[ --cmdline ]
[ --board ]
[ --base]

[ --pagesize ]

[ --ramdiskaddr]
-o|--output

exapmle
   ./mkbootimg --cmdline 'no_console_suspend=1 console=null' --kernel zImage --ramdisk boot/boot.img-ramdisk.gz -o boot.img --base 02e00000

