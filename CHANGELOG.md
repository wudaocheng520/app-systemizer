# 应用固化 更新日志

## v1.0 (versionCode 1)

- 基于 App Systemizer 1.2.8 的二改版本，模块名「应用固化」，作者「无爱」
- 安装时检测元模块（nomount / hybrid_mount / magic_mount_rs），缺失则自动下载并安装 NoMount（最后一步执行）
- WebUI 全量 Miuix 风格，叠加液态玻璃视觉
- 打开 WebUI 自动检测更新，可忽略同一版本；支持一键下载并自动安装
- 更新检查支持 GitHub 直连 / gh-proxy / jsDelivr 多级镜像回退