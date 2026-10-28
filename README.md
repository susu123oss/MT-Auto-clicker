<h1 align="center">MT AutoClicker · MT 连点器</h1>

<p align="center">
  <strong>看得见，识别得出，触控得到。把重复操作交给智能自动化。</strong>
</p>

<p align="center">
  连点 · 手势 · 找图 · 找色 · 文字识别 · 悬浮控制<br>
  从固定点击到根据画面执行下一步，让 iPhone 自动化更进一步。
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/Version-v1.1.6-0A84FF?style=flat-square">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-14%2B-111111?style=flat-square&logo=apple">
  <img alt="Install" src="https://img.shields.io/badge/Install-TrollStore%20%7C%20DEB-5E5CE6?style=flat-square">
  <img alt="Language" src="https://img.shields.io/badge/Language-中文-34C759?style=flat-square">
</p>

<p align="center">
  <a href="#mt-家族--mt-family">MT 家族</a> ·
  <a href="#最新版本">最新版本</a> ·
  <a href="#下载与安装">下载与安装</a> ·
  <a href="#mt-连点器是什么">产品介绍</a> ·
  <a href="#核心体验">核心体验</a> ·
  <a href="#适用场景">适用场景</a> ·
  <a href="#兼容性">兼容性</a>
</p>

> 本仓库用于 **MT 连点器正式版本发布与下载**。  
> 这里不提供项目源码、内部实现、构建方式或技术细节。

---

## 最新版本

### v1.1.6 · 最新公开正式版

<p align="center">
  <a href="https://github.com/susu123oss/MT-Auto-clicker/releases/latest"><strong>前往 Releases 下载最新版本</strong></a>
</p>

**v1.1.6 更新亮点**

- **新增三种越狱安装包**：在 TrollStore TIPA 之外，正式提供 rootful、rootless、RootHide DEB。
- **触摸更精准**：改善设备侧点击与手势执行的准确度和响应体验。
- **长时间运行更稳定**：优化后台运行与内存占用，减少持续找图、找字及多轮任务中的异常退出风险。
- **体验持续打磨**：兼顾悬浮操作、不同设备和横竖屏使用场景。

[查看 v1.1.6 版本发布说明](https://github.com/susu123oss/MT-Auto-clicker/releases/tag/1.1.6) · [前往最新下载](https://github.com/susu123oss/MT-Auto-clicker/releases/latest)

---

## MT 家族 · MT Family

**一套面向 iPhone 的工程与自动化生态，三款各司其职的独立产品。**

| 产品 | 核心定位 | 适合做什么 | 下载 |
| --- | --- | --- | --- |
| **MT 智能体 · MT Agent** | AI 工程中枢 | 理解项目、分析日志、协助编程、调用工具与 Runtime | [查看 MT Agent](https://github.com/susu123oss/MT-Agent) |
| **MT 内存工具 · MemoryToolkit** | 真机动态分析工作台 | 内存搜索、稳定定位、断点、ARM64 分析与 MCP 调试 | [查看 MemoryToolkit](https://github.com/susu123oss/MemoryToolkit-Release) |
| **MT 连点器 · AutoClicker** | 视觉与触摸自动化 | 连点、手势、找图、找色、OCR 与设备侧流程执行 | [查看 AutoClicker](https://github.com/susu123oss/MT-Auto-clicker) |

**理解与编排（Agent） × 运行时观察（MemoryToolkit） × 设备侧执行（AutoClicker）**

三款产品分别安装、独立更新。按需组合即可：需要真机动态分析时，可使用 MT 内存工具提供的 MCP 调试能力与 Agent 协作；连点器则专注视觉识别和触摸自动化，不依赖安装另外两款 App。

---

## MT 连点器是什么

MT 连点器是一款面向 iPhone 的智能自动操作工具。

它不只是“自动点几下屏幕”，而是希望把一连串重复、机械、需要持续盯着屏幕完成的操作，整理成更自然、更稳定、更高效的自动化体验。

从简单的连续点击，到长按、双击、滑动、拖拽、多点操作，再到根据画面中的图片、颜色或文字决定下一步动作，MT 连点器希望把常见的手机自动操作集中到一个统一入口里。

<p align="center">
  <strong>重复的事情交给 MT，真正需要判断的事情留给你。</strong>
</p>

---

## 核心体验

### 智能连点

适合需要持续点击、连续触发或固定位置重复操作的场景。

- 连续点击
- 多位置点击
- 自定义执行节奏
- 长时间任务运行
- 任务状态快速查看

### 丰富手势

不局限于单一点击，可以组合更接近真实操作习惯的动作。

- 点击
- 双击
- 长按
- 滑动
- 拖拽
- 多点操作

### 画面识别

让自动化不再只是“固定坐标执行”。

MT 可以根据屏幕中出现的内容决定何时继续下一步，例如：

- 找图
- 找色
- 找字
- 指定区域识别
- 识别后继续执行动作

这让自动操作可以更好地适应界面变化，而不是只能机械重复。

### 文字识别

对于需要根据屏幕文字继续操作的场景，可以直接使用文字识别能力辅助任务判断。

无需一直守在屏幕前确认某段文字是否已经出现，让流程更自然。

### 悬浮操作

运行任务时，可以通过悬浮入口快速查看和控制当前状态。

不用频繁在多个页面之间切换，启动、查看、控制和结束任务都更直接。

### 系统输入体验

需要输入文字时，依然可以使用熟悉的系统输入体验。

支持中文输入、输入法切换以及常用的复制、粘贴、全选等操作，让自动化流程与日常使用方式保持一致。

### 横竖屏与主题

无论竖屏还是横屏，都尽量保持自然的操作体验。

同时支持浅色与深色界面，让 MT 在不同使用环境下都保持统一、清晰。

---

## 适用场景

MT 连点器适合处理那些 **高频、重复、固定、需要持续执行** 的操作，例如：

- 重复点击与固定手势
- App 界面测试与回归验证
- 连续操作流程演示
- 等待指定图片、颜色或文字出现后继续
- 需要长时间运行的重复任务
- 需要减少人工重复操作的日常自动化场景

它的价值不在于“点得更快”，而在于把原本需要反复手动完成的动作，变成一套更省心的执行流程。

---

## 下载与安装

请从本仓库的 [Releases](https://github.com/susu123oss/MT-Auto-clicker/releases) 页面下载最新正式版本。

| 项目 | 当前说明 |
| --- | --- |
| **TrollStore** | `MTAutoClicker-v1.1.6.tipa` |
| **rootful 越狱** | `MTAutoClicker-v1.1.6-rootful.deb` |
| **rootless 越狱** | `MTAutoClicker-v1.1.6-rootless.deb` |
| **RootHide** | `MTAutoClicker-v1.1.6-roothide.deb` |

**最低系统：iOS 14.0**。TrollStore 用户安装 TIPA；越狱用户使用与环境对应的 DEB，通过兼容的包管理器安装。

> 上表为公开 v1.1.6 Release **实际附件名称**。此后本地构建命名可能不同，下载时请以对应 Release 页面为准；不同安装环境的软件包不要混装。

> 不建议从来源不明的第三方渠道获取安装包。正式版本与更新说明以本仓库 Releases 为准。

---

## 兼容性

MT 连点器以真实 iPhone 使用体验为主要目标。

当前正式版本面向：

- iOS 14.0 及以上系统
- TrollStore 或支持的越狱安装环境
- iPhone arm64 设备

不同系统版本、设备型号、前台应用和输入环境可能存在差异。  
如果遇到异常，建议先更新到最新版本后再进行验证。

---

## 关于版本更新

本下载仓库只关注正式版本交付。

每次发布会优先说明用户真正关心的内容：

- 新增了什么
- 哪些体验得到优化
- 修复了哪些问题
- 是否有需要注意的兼容性变化

不会在下载仓库中公开内部架构、实现方案、构建流程或其他开发细节。

---

## 使用边界

MT 连点器是一款通用自动操作工具。

请仅在你拥有、管理或已经获得明确许可的设备、应用与测试场景中使用，并遵守当地法律法规、平台规则以及目标应用的使用条款。

请勿用于破坏公平性、绕过限制、骚扰他人、未经授权操作第三方账户或其他不当用途。

---

<p align="center">
  <strong>MT AutoClicker · MT Family</strong><br>
  See. Recognize. Touch. Automate.<br>
  让重复操作自动完成，让每一次点击都更有价值.
</p>
