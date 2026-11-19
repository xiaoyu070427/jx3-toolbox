# 剑网三小工具

成就、挂件、角色信息一站式查询的 Windows 桌面工具（Python + PySide6）。

## 下载

最新版在本仓库的 [Releases](https://github.com/xiaoyu070427/jx3-toolbox/releases/latest) 页面，
文件名 `jx3-toolbox.exe`，单文件免安装，双击即用。

## 自动更新清单

程序启动时会读取：

```
https://github.com/xiaoyu070427/jx3-toolbox/releases/latest/download/latest.json
```

`latest.json` 随每次发布一起上传，字段：`ver` / `url` / `size` / `sha256` / `notes`。

## 数据存放

配置与缓存都在 `%APPDATA%\JX3KeyMover\`，升级或重装程序不会丢。
