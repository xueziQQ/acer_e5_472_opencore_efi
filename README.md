# ACER_E5_472_opencore_efi

#### 介绍
宏基笔记本Acer_e5_472(pm246)黑苹果opencore 0.60引导efi

#### 硬件配置
CPU:i5 4210m
GPU：HD4600/GT820m 2G
ETH Card：rtl8111
WIFI/BLUETOOTH: AR9565
HD: 500G
MEMORY: 4G DDR3L 1600
WEBCAM
cardreader


#### 使用说明

1.  opencore 引导在黑果小兵引导文件基础上修改正常引导10.15.6/10.15.7
2.  DSDT/SSDT 自己提取，未做太多修改
3.  CPU变频正常、核显正常、网卡正常、WIFI蓝牙正常驱动（但是有冲突，同一时间只能工作一个）、触摸板驱动正常（多指手势无法工作）、液晶屏幕背光可以在设置面板中调节
4.  睡眠未调试、读卡器不工作、airdrop等都未调试

#### 致谢

1.  https://github.com/acidanthera/OpenCorePkg
2.  https://oc.skk.moe/
3.  https://blog.xjn819.com/post/opencore-guide.html
4.  https://www.yundongfang.com/Yun9619.html
