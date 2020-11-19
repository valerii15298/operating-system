# operating-system

usage in gcloud:
 1. nasm -f bin boot1.asm -o boot1.bin
 2. qemu-system-x86_64 -curses -drive format=raw,file=boot1.bin,index=0,if=floppy
 
 And to exit from that, use ESC + 2 then q + ENTER
# operating-system
