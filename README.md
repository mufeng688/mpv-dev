## 日志

本项目基于[mpv-config](https://github.com/dyphire/mpv-config) & [mpv](https://github.com/mpv-player/mpv)修改

V0.5.1 beta:

* 回滚调整cache目录
* 更新mpv, ffmpeg, yt-dlp
* 更新uosc(MPV_lazy版本)
* 同步mpv-config上的mpv.conf上的修改

V0.5.0 beta:

* 同步mpv-config上的mpv.conf上的修改
* 更新部分脚本文件为最新版本
* 启用HDR直通参数配置组，部分设备可能出现颜色偏差
* 关闭Target色彩管理配置组
* 更新mpv, ffmpeg, yt-dlp

V0.4.1 beta:

* 修改thumbfast.conf里的network为yes，在网络播放时启用略缩图
* 加入[MPV-Play-BiliBili-Comments](https://github.com/itKelis/MPV-Play-BiliBili-Comments)的支持，需要配合[Play-With-MPV](https://github.com/LuckyPuppy514/Play-With-MPV)使用
* 修复让弹幕60帧显示

V0.4.0 beta:

* bug修复

V0.3.0 beta:

* 并入[MPV_lazy](https://github.com/hooke007/MPV_lazy)中的vs滤镜包（包含补帧-MVTools_快速，补帧-MVTools_标准，补帧-RIFE_标准）
* 调整cache目录为_cache

V0.2.0 beta：

* 修复manager.json部分无法更新的链接（连接到我的GitHub的fork项目），部分项目可能有做修改

V0.1.0 beta：

* 为emby播放记录notify_media.lua已被移入archive文件夹
