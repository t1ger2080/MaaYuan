<!-- markdownlint-disable MD033 MD041 -->

<div align="center">

# MaaYuan

</div>

基于 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 的代号鸢/如鸢小助手。图像技术 + 模拟控制，解放双手！

Windows 端图形界面采用 **[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)**。

建议将模拟器分辨率配置固定为`16:9`或`9：16`。

## 功能介绍

- 刷 6-24 直到体力耗尽（不会消耗白金币回体力）

  - [x] 随时随地一键开刷，可在日常结束后自动进入 6-24，刷光剩余体力
  - [x] 关卡内自动接管开关

- 一键清日常（开启无限循环时会自动吃鸟食，但不会消耗白金币买鸟食）

  - [x] 模拟器、游戏自启动
  - [x] 清鸟食
    - [x] 突发情况（漆园蝶） ✅ 无限循环开关
    - [x] 小道消息 ✅ 无限循环开关
    - [x] 他的传闻 ✅ 无限循环开关
    - [x] 代办公务 ✅ 公务自定义选项 ✅ 无限循环开关
  - [x] 【需月卡】领取每日体力福利
  - [x] 领取每日进膳体力
  - [ ] 收据点
    - [x] 收取据点资源
    - [x] 派遣洛阳/寿春/广陵（体力不足自动停止）
    - [ ] 据点情报 （只做 3 星？）
  - [x] 刷历练 （✅ 自定义关卡 + 等级 + 次数）
  - [ ] 观星 （点一下 / 消耗 20w 金币？）
  - [x] 相见互动
  - [ ] 家具互动
  - [ ] 每日分享
  - [ ] 密探升级（首位展示密探？）
  - [ ] 【港服限定】扫荡白鹄
  - [ ] 【港服限定】心纸营建历险
  - [ ] 领取日活奖励

- 地宫限定日常

  - [ ] 【地宫限定】扫荡地宫 （自定义关卡？）
  - [ ] 【地宫限定】雀部解密
  - [ ] 【地宫限定】领取日活奖励

- 楼主查岗追加日常（？）

  - [ ] 【楼主查岗】领取额外 100 体力开关
  - [ ] 【楼主查岗】补齐 5 次历练

- 当期活动

  - [x] 【如鸢】三千世界刷成就

- 不太适合自动化的任务？
  - 赠送密探礼物
  - 消耗 200 白金币

## 使用说明

### Windows（✅ 有可视化界面）

- 对于绝大部分用户，请下载 `MaaYuan-win-x86_64-vXXX.zip`
- 若确定自己的电脑是 arm 架构，请下载 `MaaYuan-win-aarch64-vXXX.zip`

请注意！Windows 的电脑几乎全都是 x86_64 的，可能占 99.999%，除非你非常确定自己是 arm，否则别下这个！

解压后运行 `MaaYuan.exe` 即可。

如果遇到报错，可能是没有安装`.NET 桌面运行时 8`。

请安装 [`Visual C++ 可再发行程序包`](https://aka.ms/vs/17/release/vc_redist.x64.exe) 和 [`.NET 桌面运行时 8`](https://aka.ms/vs/17/release/vc_redist.x64.exe) 并 **重新启动计算机** 后再次运行 `MaaYuan.exe`。

推荐使用 Windows 10 或 11 的用户使用 winget 工具进行安装，只需在终端中运行以下命令。

```
winget install Microsoft.VCRedist.2015+.x64 Microsoft.DotNet.DesktopRuntime.8
```

### MacOS（❌ 无可视化界面）

- 若使用 Intel 处理器，请下载 `MaaYuan-macos-x86_64-vXXX.zip`
- 若使用 M1, M2 等 arm 处理器，请下载 `MaaYuan-macos-aarch64-vXXX.zip`
- 使用方式：
  ```
  chmod a+x MaaPiCli
  ./MaaPiCli
  ```

~~我抄隔壁的我没 mac，欢迎测试反馈~~

### Linux （❌ 无可视化界面）

~~差不多同上吧大概，我用 wsl 的，欢迎测试反馈~~

## 从零开始学会写作业

1. [准备工作](./docs/1.1-准备工作.md)
2. 编写你的第一份日常行动作业
3. 编写你的第一份战斗关卡作业
4. 利用通用模块，快速实现常规功能

   4.1 [日常行动通用模块](./docs/4.1-日常行动通用模块.md)

   4.2 战斗行动通用模块

5. 把你的作业加入作业列表中
6. 向本项目贡献代码

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！图形界面由 **[MFAWPF](https://github.com/SweetSmellFox/MFAWPF)** 提供。

感谢以下开发者对本项目作出的贡献:

<a href="https://github.com/syoius/MaaYuan/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=syoius/MaaYuan&max=1000&columns=15&anon=1" />
</a>
