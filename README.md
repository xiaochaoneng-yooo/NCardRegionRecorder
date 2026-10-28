# NCardRegionRecorder — Windows 11 NVIDIA 区域录屏

> **Windows 二进制发行仓库（仅提供应用下载，不公开主程序源代码）。** 此仓库不是开源代码仓库。

一个用于 Windows 11 的 NVIDIA NVENC 区域/窗口录屏工具，提供按比例拖动框选、系统声音和麦克风录制功能。不是 NVIDIA 官方软件。

## 下载 Windows 便携版

**[下载 NCardRegionRecorder v1.7-ratio（Windows x64 ZIP）](https://github.com/xiaochaoneng-yooo/NCardRegionRecorder/releases/download/v1.7-ratio/NCardRegionRecorder_v1.7_ratio_win64.zip)**

也可查看 [正式 Release 页面](https://github.com/xiaochaoneng-yooo/NCardRegionRecorder/releases/tag/v1.7-ratio)。

文件名：`NCardRegionRecorder_v1.7_ratio_win64.zip`  
文件大小：91,518,984 字节（约 87.3 MiB）  
SHA-256：`12d1dd4a8af73d6b0c3175a2cb672ab8d61a92cf41fea0e2c1a192011b899af9`

## 使用方法

1. 下载上面的 ZIP，**完整解压**至一个文件夹。
2. 双击 `NCardRegionRecorder.exe`，不要仅复制或单独移动 EXE。
3. 需要保留同级 `_internal` 与 `tools` 文件夹，程序才能运行。
4. 在程序界面选择框选屏幕区域，以及 `16:9`、`9:16`、`4:3`、`3:4`、`1:1`、`21:9`、自定义或自由比例。拖动选择区域后开始录制，视频保存在自己设置的本地目录。

**系统要求**：Windows 11 x64，支持 NVENC 的 NVIDIA 显卡和对应驱动。压缩包自带运行库、FFmpeg、FFprobe，无需单独安装 Python。

## 版本说明

`v1.7-ratio` 增加固定比例及自定义比例的录制区域框选，改善多屏幕框选，并保留 NVENC 与声音录制功能。

已验证发行包可在 Windows 11 上打开/关闭窗口，并能首次创建用户配置；未对所有显卡型号、音视频组合进行完整实录验证。

## 代码与第三方许可

此公开仓库只提供下载信息。**NCardRegionRecorder 主程序源代码不在 GitHub 上公开，也不授予主程序源代码的复制或修改许可。** 已发布的可执行文件包含 Python 运行时和第三方软件组件；必要的第三方许可信息随 ZIP 附带（特别是 FFmpeg 的 GPLv3、windows-capture 的 MIT 许可）。第三方组件的原始许可证不受本项目此说明限制。详细来源及许可信息见压缩包内的 `THIRD_PARTY.md`、`THIRD_PARTY_LICENSES`、`third_party_licenses` 与 `tools/LICENSE`。

如需报告问题，请使用 GitHub Issues，避免提交个人录制视频、账号、密钥或敏感日志。
