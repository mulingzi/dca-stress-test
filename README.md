<div align="center">

# 📊 DCA Stress Test | 定投压力测试器

**Would your DCA strategy survive a market crash?**
**如果在暴跌前一天开始定投，最后会怎样？**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with AI](https://img.shields.io/badge/Made%20with-Claude%20AI-blueviolet)](https://claude.ai)
[![GitHub Stars](https://img.shields.io/github/stars/mulingzi/dca-stress-test?style=social)](https://github.com/mulingzi/dca-stress-test)

[🚀 Live Demo](https://mulingzi.github.io/dca-stress-test) · [中文说明](#中文说明) · [English](#english)

<img src="preview.png" alt="DCA Stress Test Preview" width="720">

</div>

---

## 中文说明

### 这是什么？

一个**单文件 HTML 定投压力测试工具**，用纳斯达克 100 指数 **2000–2026 年真实月度数据**，模拟在历史上最糟糕的时间点开始定投会发生什么。

不是鸡汤，不是模拟曲线，是真实价格、真实跌幅、真实回本周期。

### 为什么做这个？

刚开始定投的时候，每天被各种消息轰炸——涨了怕错过，跌了怕套牢，买了又卖、卖了又买。

后来想明白了：**与其焦虑，不如用数据看看最坏情况到底能坏到什么程度。**

搜不到这样的工具，就自己用 AI 做了一个。

### 核心功能

| 功能 | 说明 |
|------|------|
| 🔥 **4 次真实崩盘模拟** | 2000 互联网泡沫 · 2008 金融危机 · 2020 新冠+加息 · 2022 加息周期 |
| 📊 **真实历史数据** | 纳斯达克 100 指数 245 个月度数据点，非模拟曲线 |
| 💰 **初始投入 + 月定投** | 支持一次性投入 + 每月定投的真实场景 |
| 🎯 **分级补仓策略** | 跌 5% / 10% / 20% / 30% 四档自动补仓，智能推荐金额 |
| 📈 **收入增长复利** | 年薪涨幅同步调整定投金额 |
| ⚔️ **四次崩盘一键对比** | 同参数横向对比四次崩盘表现 |
| 🎯 **目标规划计算器** | 输入目标金额和年限，反推每月需要投多少 |
| 📱 **移动端适配** | 手机电脑都能用，响应式布局 |

### 一个让人意外的结论

以月投 ¥3,000 为例，在 2000 年 3 月互联网泡沫的**最高点**开始定投——

- 中间最大浮亏超过 **-40%**
- 但坚持到 2005 年底，**最终盈利约 ¥48,000**

历史上最倒霉的入场时机，定投到最后还是正收益。

> ⚠️ 历史数据不代表未来表现。本工具仅供学习研究，不构成任何投资建议。

### 使用方式

**方式一：在线使用**

访问 [GitHub Pages](https://mulingzi.github.io/dca-stress-test) 直接打开

**方式二：本地使用**

```bash
git clone https://github.com/mulingzi/dca-stress-test.git
open index.html
```

没错，就这么简单。单文件，无依赖，无需安装。

### 技术细节

- **纯前端**：单文件 HTML + CSS + JavaScript，零外部依赖
- **数据来源**：Yahoo Finance API（NDX 月度收盘价）
- **图表渲染**：原生 Canvas，无第三方图表库
- **体积**：~50KB，秒开
- **AI 辅助开发**：使用 Claude 完成需求梳理、代码开发、数据验证、压力测试

---

## English

### What is this?

A **single-file HTML tool** that stress-tests Dollar-Cost Averaging (DCA) strategies using **real monthly NASDAQ-100 data from 2000 to 2026**. It simulates what happens when you start investing at the absolute worst timing in history — right before a major crash.

No fake curves. No motivational fluff. Just real prices, real drawdowns, and real recovery timelines.

### Features

- **4 Historical Crash Scenarios** — Dot-com Bubble (2000) · Global Financial Crisis (2008) · COVID + Rate Hikes (2020) · 2022 Rate Cycle
- **Real Market Data** — 245 monthly data points from NASDAQ-100, not simulated curves
- **Initial Lump Sum + Monthly DCA** — Model real-world scenarios with existing savings + recurring investment
- **Tiered Dip-Buying Strategy** — Auto-buy more at -5% / -10% / -20% / -30% drawdowns with smart amount recommendations
- **Income Growth Modeling** — Annual salary growth compounds into DCA amount
- **4-Crash Side-by-Side Comparison** — Compare all scenarios with identical parameters
- **Goal Planning Calculator** — Reverse-calculate monthly investment needed for a target amount
- **Mobile Responsive** — Works on phone and desktop, no installation required

### A Surprising Finding

Starting a ¥3,000/month DCA at the **peak of the dot-com bubble** (March 2000):

- Maximum drawdown exceeded **-40%**
- But holding through to Dec 2005: **net profit ≈ ¥48,000**

The worst possible entry timing in history — and DCA still ended in the green.

> ⚠️ Past performance does not guarantee future results. This tool is for educational purposes only and does not constitute investment advice.

### Quick Start

**Option 1: Online** — Visit the [live demo](https://mulingzi.github.io/dca-stress-test)

**Option 2: Local**

```bash
git clone https://github.com/mulingzi/dca-stress-test.git
open index.html
```

Single file. Zero dependencies. No build step.

### Tech Stack

| | |
|---|---|
| Frontend | Vanilla HTML/CSS/JS, single file |
| Data | Yahoo Finance API (NDX monthly close) |
| Charts | Native Canvas API |
| Size | ~50KB |
| AI-Assisted | Built with Claude |

---

<div align="center">

### ⭐ Star this repo to get notified when data updates or new features drop

如果觉得有用，点个 ⭐ Star 可以收到数据更新和新功能的通知

---

**Made with ❤️ and AI**

</div>
