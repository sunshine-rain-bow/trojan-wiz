﻿# trojan-wiz
一键安装trojan-gfw v2.0
## 安装前必须打开服务器的80和443端口
请参考：[视频教程](https://youtu.be/x-2qX6iqxgA) [视频教程2](https://youtu.be/zzF3AMf0_qI)
- 已经添加自动续期功能，并且客户端无需下载证书。直接复制最后一屏的配置信息，在客户端创建client.json即可，无需再去下载证书。
- 已经将trojan使用简化到极限
- trojan无流量特证，流量完全是https流量，这是翻墙的最终境界

## 更新日志：
- 2019-4-30 2.1beta发布，升级trojan到1.12.1，添加删除trojan功能
---
# 安装命令：
>正式版脚本： wget -N --no-check-certificate https://raw.githubusercontent.com/sunshine-rain-bow/trojan-wiz/master/ins.sh && chmod +x ins.sh && sudo bash  ins.sh

>beta版本：wget -N --no-check-certificate https://raw.githubusercontent.com/sunshine-rain-bow/trojan-wiz/master/ins_beta.sh && chmod +x ins_beta.sh && sudo bash  ins_beta.sh
---
支持的系统：
- ubuntu 16.04+
- debian 9(理论上应该支持debian 8)
- centos 7+
- RHEL 7+
