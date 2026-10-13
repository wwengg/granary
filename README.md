# Granary

在 **HarmonyOS NEXT（纯血鸿蒙）** 手机 / 平板 / PC 上运行 **PC 版**《星露谷物语》的启动器。

<!-- TODO: 实机录屏截图，建议原创像素风封面 + 游戏内实拍 -->
![screenshot](docs/screenshot.png)

## 功能特性

- 完整运行 PC 版星露谷物语（1.6.15 实测），OpenGL 渲染，实测 60fps
- 蓝牙 / USB 键鼠直连，桌面级操作体验
- 触屏虚拟手柄模式——不带键盘也能玩（左摇杆 + 常用按键图层，游戏原生手柄支持）
- SMAPI 4.5.2 mod 支持，兼容桌面 mod（Linux 代码路径）
- 联机可用（含 Lidgren 网络栈所需的 OpenSSL / LZ4 原生库）

## 系统要求

- HarmonyOS NEXT 手机 / 平板 / PC（已在 Mate X6 手机、MatePad（MRDI-W00）平板、PC 实测）
- 蓝牙或 USB 键鼠（可选，触屏模式可不接）
- 预留约 4GB 存储空间（应用 + .NET 运行时 + 游戏文件）

## 安装（侧载）

Granary 不上架华为应用市场，需要侧载安装：

1. 下载 Release 中的 `.hap` 安装包
2. 按照侧载教程安装：<https://www.sydxky.cn>（国内推荐渠道，含完整教程）
3. 安装后在桌面出现 Granary 图标

## 游戏文件准备（重要）

Granary **不包含任何游戏文件**。你需要：

- 自行拥有 PC 版星露谷物语（[Steam](https://store.steampowered.com/app/413150/) 正版）
- 在启动器中通过「选择目录」或「zip 导入」将游戏文件传入应用沙箱

## 免责声明

- 本项目为非官方第三方工具，与 ConcernedApe、Chucklefish 无任何关联
- 《星露谷物语》(Stardew Valley) 名称与内容版权归原作者所有
- 本工具仅提供运行环境，不分发、不包含任何游戏资产，请支持正版
- 本工具**永久免费**，仅供个人学习交流使用，**禁止任何形式的售卖或捆绑收费**

## 已知问题与计划

- [ ] Steam 登录直接下载游戏（开发中）

问题反馈请提 [Issues](../../issues)。

## 致谢

- [Cinderbox (Android)](https://www.nexusmods.com/stardewvalley/mods/43278) / [Ekyso/Cinderbox](https://github.com/Ekyso/Cinderbox) —— 安卓版先行者，本项目架构参考
- [SMAPI](https://smapi.io/) —— mod 加载框架
- [SDL3](https://www.libsdl.org/) / [OpenAL Soft](https://openal-soft.org/) / [.NET 运行时](https://dotnet.microsoft.com/) / OpenSSL / lz4

## 许可证

本仓库仅发布二进制安装包，源代码不开源。所含第三方开源组件的许可证见 [THIRD_PARTY.md](THIRD_PARTY.md)。
