su -c "mount -o remount,rw /"
su -c "mount -o remount,rw /system"
su -c "ln -s /debug_ramdisk/su /system/bin/su"
