# ha-backup-restore

本工具可以用来备份和恢复Home Assistant的配置文件，由于我发布的固件更新频率较高，所以建议大家使用这个工具来备份和恢复。

# 使用方法
准备一个U盘连接到斐讯N1或者树莓派的USB口，U盘格式为FAT32格式。 

#执行下面命令赋予脚本执行权限

sudo chmod +x ha_usb_backup.sh ha_usb_restore.sh  

#运行ha_usb_backup.sh即备份到U盘hassbackup目录下.

bash ha_usb_backup.sh

#运行ha_usb_restore.sh 即恢复最新一次备份到Home Assistant。 

bash ha_usb_restore.sh

