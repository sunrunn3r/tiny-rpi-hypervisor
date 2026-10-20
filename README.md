# tiny-rpi-hypervisor

This is a personal project to create a minimal hypervisor for the raspberryPI 4B and QEMU
adding others if I have one. 

No specific aim yet but as always the act of doing this is a learning experience. 
Right now it boots on Qemu starts a simple console and runs a 'hello world' level 
guest to confirm its working.

Now need to add the device information to the guest memory so it'll be able to at least 
begin to boot a Linux guest (even if its not yet presenting much more than a virtual 
serial port and framebuffer).
