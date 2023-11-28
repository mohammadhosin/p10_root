#p10_root
#Magisk
Root Huawei P10 VTR-L29 with Magisk


Preparation of Huawei P10:
1. First you should take a backup of your phone.
2. Your phone battery should be charge minimum 80%.
3. Make sure proper power backup of your PC.

Step 1: Download and install Huawei P10 ADB driver on your PC and enable Developer option and USB debugging mode on your Huawei P10 by this guide and enable Oem unlocking option.
https://developer.android.com/studio/releases/platform-tools

Now download and extract Magisk Recovery and Fast-boot tool and move Magisk Recovery (Magisk.img) file in the Fast-boot tool folder.
Then press and hold shift key in the keyboard and right click in the extracted Fast boot tool folder and select “Open command window here”.

adb reboot bootloader

fastboot flash recovery_ramdisk Magisk.img

fastboot reboot

adb reboot recovery


and run Magisk app in p10 
done.
