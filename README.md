# Hackintosh


### 配置清单:

- 主板: 技嘉Z370N WiFi
- CPU: i7-8700
- 硬盘: 三星 NVMe970 EVO 250G
- 内存: 海盗船复仇者 LPX DDR4 3000 16G x 2
- 网卡: BCM94360CD + M.2转换卡
- 散热器: 猫头鹰 NH-L9i
- 电源: 海盗船SF600
- 显卡: RX560

### 升级主板BIOS为Z370NWF.14b，升级后需要解锁CFG lock

教程参考：https://dortania.github.io/OpenCore-Post-Install/misc/msr-lock.html#checking-if-your-firmware-supports-cfg-lock-unlocking


### BIOS设置:

- Initial Display Output -> PCIe 1 Slot
- DVMT Pre-Allocated -> 128M
- DVMT Total Gfx Mem -> 128M

- Above 4G decoding	-> Enable
- EHCI/XHCI Hand-off -> Enable

- VT-d -> disabled
- Wake on LAN Enable -> Disabled
- CSM -> Disabled

### 定制USB:

教程参考：https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html

![](usb.png)


### 感谢:

[https://blog.xjn819.com/?p=543](https://blog.xjn819.com/?p=543)
