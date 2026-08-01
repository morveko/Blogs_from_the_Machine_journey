# Built the builder
**Date:** 31/07/2026

iv been learning linux and cyber security. for a while iv been curious about arch and VMs as i heard you build your own desktop environment on arch and also saw some yt videos.
i thought i will 
```bash
pacman -S kitty waybar blahblah
```
and i will get it running or did i?
i decided to do it fully manually instead of running an installer and press next i will install Arch from scratch.
so after making n deleting 3 VMs there i finally was in the final VM with perfect conditions.

---

## WHat i did and learned

- GPT partitioning
- EFI System Partition
- Mounting
- pacstrap
- chroot
- fstab
- systemd-boot

![ArchbootfromISO](31_07_26_ArchVM/SS/VirtualBox_ArchLinx_01_08_2026_04_25_36.png)

---

## Cool story
while doing this stuff i had to copy UUID which is a big line of random alphabets and there was no copy paste option in base arch so most likely i could have wrote that chunk of randomness
but thats manual labor and i thought naah we dont do what machine can do for us we automate.

Automatic UUID insertion:

```bash
UUID=$(blkid -s UUID -o value /dev/sda2)
```
What an irony of a guy talking about automating while installing arch by hand.

## Closure
So after spending 4 to 5 hours manually doing something a normal person using an installer would have done in 30mins and didnt even reach the cool part of getting kitty and stuff 
there i was after manually setting up arch with internet not configured yet and arch still looking like arch with no cool rice half way there

![Archbuilt](31_07_26_ArchVM/SS/VirtualBox_ArchLinx_01_08_2026_05_03_22.png)

all i have to say is
it was good learning 
atleast now i can say i use Arch btw.
