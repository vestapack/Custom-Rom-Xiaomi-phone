# How to install a PE on note 8 pro without freaking problem

1.  Logout and login xiaomi acc

2.  OEM unlock + bind to this device

3.  XiaoMiTools V2 install driver
#### (Xiaomitools v2 (java))https://www.xiaomitool.com/V2/#download

4.  MiFlash Unlock (offical tools) wait 7 days to unlock
#### (offical unlock)https://en.miui.com/unlock/download_en.html
#### (Rom download) https://c.mi.com/us/miuidownload/detail?guide=2

5.  Xiaomitools v2 my phone bricked- install latest miui

6.  Logout xiaomi acc (I needed to)

7.  Fastboot flash recovery twrp.img
#### (adb and fastboot app)https://developer.android.com/studio/releases/platform-tools
    use cmd to open this directory and run
    
8.  fastboot reboot recovery

9.  Wipe cache, system, vendor + Sd card PixelExperience.zip install
#### or open ADB sideload option
   -- adb sideload PixelExperience.zip
   
10. Format data (In wipe) if failed \-- fastboot format userdata

11. [command]Ready to go
