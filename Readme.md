# **Hackintosh 10.15 Catalina for HP ZHAN99 MOBILE WORKSTATION Zbook15VG5**

============================================

[CN版请前往我blog查看](https://xtremedev.top/default/107.html)

# **IMPORTANT**

If this is the first time you try to install Hackintosh, please prepare well for some basic knowledge, such as some concept about Hackintosh and the installation of it. Better to go to some forms like tonymacx86 or insanelymac for more information and helps.

# **PROBLEMS**

1. Sometimes the volume may not work.Please reboot.

2. Sometimes PM981 with nvmeassert failed in booting.Please reboot

3. Sometimes Touchpad crashed,please flashing kext cache and reboot.

4. If you can't bear the voodoops2's bug,please delete all voodoo drivers and use the appleps2 in kext/other/backup

5. If you want test thunderbolt 3,please put the IOElectrify driver from kext/other/backup to kext/other

# Install

**If your computer is using PM981, the first thing you need to do is prepare another hard driver (SSD or HDD) in the SATA connector, or exteral HD.(Don't prepare a PM981 again)**


1. Create a USB disk to install macOS.(if get nvme assert failed,please put ssdt-nvme.aml and Hacknvmefamily from my efi to install disk's efi)

2. Install it on the other disk that you have prepared.

3. After installation, Don't boot into MacOS! Back to Windows and install the Paragon Hard Disk Manager™ 16. Backup the partition that you intalled the macOS and then create a new partition 

4. Copy Clover-boot folder to the EFI partition of your computer, using EasyUEFI to create a new boot item. 

5. Reboot to macos,and pass the setupwized

6. Reboot to Windows and delete clover-boot,then put the clover folder to the efi partition.

7. Edit your bootitem then you can boot your MacOS

=============================================

#**AFTER INSTALLATION**

you need prepare Clover Configrator and Hackintool.

Please download them manually.

1. Don't connect to the Internet !

2. Use Clover Configrator ,click the Home button in the corner and select the config.plist.Choose the SMBIOS in the sidebar, press these two "generate new", save it.

3. Then generate new uuid

4. Open the hackintool Restart. And then go to the “tools" tab, click the rebuilding kexts cache.

5. Reboot and now you can connect to the Internet and login your Apple ID.

Now enjoy your Hackintosh!