# guide-elementary-persistent
Elementary OS Persistent


From https://www.reddit.com/r/elementaryos/comments/5mell3/the_final_word_on_elementaryos_as_a_live/
```
Hey guys, I've seen quite a lot of people asking the question about a truly persistent live USB of elementaryOS. Lot's of workarounds have been discussed, and various programs suggested, but I'm going to tell you for the last time how it should be done. I like having one so I can use my work laptop completely independently of the Windows 10 install on the HDD.
You will need the following software/hardware:- *A Windows PC *A copy of Oracle VM VirtualBox (free) *A copy of the eOS ISO file *A USB drive of reasonable size for running an OS from (32GB and over)
I'm going to assume a fair amount of knowledge in this quick guide, so if you're immediately lost, send me a message and i'll break it down for you.
Firstly you need to set up a new VM purely for installing eOS. It needs a 9Gb virtual HDD and USB support. That's it. Set the eOS ISO as the bootable image within settings, and fire up the VM. Check that your USB is inserted and is accesable by the VM (right-click on the little USB icon in the bottom right, make sure your USB has a tick by it) It will load to the installation screen, which you can follow as usual. When you get to the section talking about installation (It has warnings of erasing all data etc) and select the bottom option (Do something else) which will take you to the partition screen. You should see your USB drive listed here as if it was a normal HDD. Follow this guide to set up the partitions (https://itsfoss.com/guide-install-elementary-os-luna/) and proceed with installation.
That's it.
When you restart and boot from USB you will have a fully persistent live USB. Please be aware that this method does not support UEFI, so swith to Legacy in the BIOS before booting the USB.
```
