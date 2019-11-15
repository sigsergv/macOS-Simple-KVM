# Forked repo readme

Copy firmware file:

~~~~~
cp firmware/OVMF_VARS-1024x768.fd firmware/OVMF_VARS-1024x768-copy.fd
~~~~~

Bridge fix (debian/ubuntu):

~~~~~
sudo chmod u+s /usr/lib/qemu/qemu-bridge-helper
~~~~~

Use script `run.sh` to start VM. It's based on original `basic.sh`, use command `diff -u basic.sh run.sh` to see the difference.
