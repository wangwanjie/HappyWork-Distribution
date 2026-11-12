# HappyWork

本仓库只发布 HappyWork macOS 安装包，不包含应用源码。项目基于 [RustDesk](https://github.com/rustdesk/rustdesk)。

## 下载

| 架构 | 安装包 |
| --- | --- |
| Apple 芯片（arm64） | `HappyWork-<版本>-macos-arm64.dmg` |
| Intel（x86_64） | `HappyWork-<版本>-macos-x86_64.dmg` |
| Linux（x86_64） | `HappyWork-<版本>-linux-x86_64.deb` |

打开 [最新版本](https://github.com/wangwanjie/HappyWork-Distribution/releases/latest) 选择与 Mac 架构对应的 DMG。发布包经过 Developer ID 签名与 Apple 公证。

## 在线更新

HappyWork 从本仓库的最新 GitHub Release 检查 macOS 更新。Release 同时包含两个架构的 DMG、`rustdesk-update.json` 和 `rustdesk-update.json.sig`。客户端验证元数据签名、安装包 SHA-256、版本及应用身份后安装更新。签名私钥仅由发布者保管，不在此仓库中。
