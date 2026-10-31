# TikTok_TransFlow Releases

本仓库只承载 TikTok_TransFlow 的发布清单与分片安装包，不包含源码。

## 内容

- `latest.json`：客户端更新检查清单，包含版本、分片地址、大小与 sha256。
- GitHub Release `v{version}`：完整应用 zip 的分片。

## 使用

1. 按 `latest.json` 的 `assets` 顺序下载全部分片。
2. 按 `part` 编号顺序合并为 `TransFlow-{version}-win64.zip`。
3. 解压后运行 `TransFlow.exe`。
4. 使用 `latest.json` 中的 `sha256` 校验每个分片。

源码仓库为私有仓库，不在本仓库分发源码。
