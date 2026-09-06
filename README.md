# OpenWRT-CI

贝尔040G系列，深度简化版本

## 可能不稳定！建议高级玩家使用
没有XG-040G-TF测试设备
XG-040G-TF的刷机包没有经过测试，谨慎使用

移除部分存储支持和管理及其他工具包
移除手机连接支持
移除lucky和clash
移除argon主题,使用openwrt主题
添加iptables支持
移除lucky和clash
测试USB4

移除的软件包大多可以Immortalwrt下载

fork(感谢bingoguo93)
https://github.com/bingoguo93/OpenWRT-CI-XG-040G-MD

刷机前必须备份所有原厂分区，特别是ri和bosa分区

详细说明
https://www.right.com.cn/forum/thread-8453612-1-1.html

支持设备： 四个固件通用，设备名称只是区分不同功能 

带USB设备:
  XG-040G-MD  XG-140G-MD(lan4 wan)

不带USB设备: 
  XG-040G-TF  XG-140G-TF(lan4 wan)

https://github.com/bingoguo93/immortalwrt.git


# 固件简要说明

固件每天自动编译

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

贝尔040系列，140系列。

# 目录简要说明

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置

#
[![Stargazers over time](https://starchart.cc/VIKINGYFY/OpenWRT-CI.svg?variant=adaptive)](https://starchart.cc/VIKINGYFY/OpenWRT-CI)
