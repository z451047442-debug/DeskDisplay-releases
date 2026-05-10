# DeskDisplay v2.0

Windows 桌面系统监控悬浮窗 —— 半透明、不打扰的桌面小窗口，实时展示系统状态。

## 监控功能

- **CPU** — 总体使用率 + 历史折线图 + 每核心 + Top 5 进程
- **内存** — 已用/总量 + 颜色进度条 + Top 5 进程
- **网络** — 实时上传/下载速率 + 每块网卡独立显示
- **磁盘** — 所有驱动器空间
- **GPU** — 使用率 + 显存 + 多 GPU
- **电池** — 电量 + 充电状态（台式机自动隐藏）
- **系统信息** — 主机名、运行时间、Windows 版本

## 窗口特性

- 半透明悬浮窗，不在任务栏显示
- 文字/背景透明度独立调节（鼠标滚轮即可）
- 模块自由拖拽排序
- 点击穿透模式（F8）
- 全部快捷键可自定义
- 位置/配置自动保存

## 系统要求

- Windows 11 / Windows 10 (1809+)
- x64 或 x86

## 下载

前往 [Releases](../../releases) 下载最新 `DeskDisplay.exe`，双击即用，无需安装。

## 使用

右键点击悬浮窗打开菜单，所有设置即时生效。配置保存在 `%APPDATA%\DeskDisplay\settings.ini`。

## SmartScreen 警告

首次运行如果出现 Windows SmartScreen 警告：

1. 下载 `DeskDisplay.cer` 和 `install-cert.bat`
2. 右键 `install-cert.bat` → **以管理员身份运行**
3. 完成后即可正常打开，不再提示
