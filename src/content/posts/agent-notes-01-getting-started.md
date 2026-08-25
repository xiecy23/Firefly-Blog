---
title: "Agent 学习笔记 #01：一个铁路专业学生的 AI 自学路线"
published: 2026-08-24
description: "主业之外自学 AI Agent 的第一篇笔记：为什么现在入场、新手该关注哪三个信号、以及我的学习路径和第一个实战项目规划。"
tags: [AI Agent, Claude Code, 学习笔记]
category: 学习笔记
draft: false
---

## 为什么是现在

我是铁路运输专业的学生，AI 是我主业之外自学的方向。开始记这个系列，是因为最近一周的信息密度让我确信：**对新手来说，现在入场 agent 的窗口成本最低，但不会永远开着。**

## 本周观察到的三个信号

### 1. 编码 Agent 进入"默认自主"时代

Anthropic 本周给 Claude Code 推送了更自主的运行模式——agent 从"每步都要人确认"转向"接到任务自己跑完"。这不是普通的功能更新，它改变的是使用范式：以前你操作工具，以后你管理员工。

参考：[Enabling Claude Code to work more autonomously](https://www.anthropic.com/news/enabling-claude-code-to-work-more-autonomously)

### 2. 终端 Agent 与 Skills 生态正在扎堆爆发

GitHub 日榜上一天之内出现多个同类项目，Hacker News 上也是连续多日：Rust 写的多智能体引擎、树莓派上的自托管社交 Agent、甚至有人在一部安卓手机上跑起了 SQLite Agent 网格。

生态爆发期意味着两件事：教程稀缺（先写的人吃流量），轮子很多（不用从零造）。

### 3. 中文教程窗口期刚开

中文世界已经出现了成体系的入门材料，比如 [ai-agent-handbook 中文实战手册](https://github.com/Xwh630/ai-agent-handbook)和一批 Claude Code 中文教程（[从安装到熟练](https://cloud.tencent.com/developer/article/2689490)、[完全实战指南](https://cloud.tencent.com/developer/article/2639817)）。数量还不多，先学的人有内容红利。

## 我的学习路径（本周起）

1. **主教材**：ai-agent-handbook，目标是两周内跑完前三章，每章产出一篇笔记（就是你现在看到的这个系列）
2. **工具实操**：Claude Code，把日常重复流程（资料整理、信息汇总）交给它跑
3. **第一个实战项目**：一个**招聘公告聚合器**——自动盯多个官网的更新并汇总提醒。选它是因为需求真实（自己和同学都要用）、规模可控、正好覆盖抓取/解析/通知三个基本功

## 记录原则

每篇笔记只写我亲手跑通的东西，跑不通也会写清楚卡在哪。不做二手信息搬运工。

---

*本系列是我每日信息简报系统的公开切片。简报本身是私有的，但值得公开的学习过程会出现在这里。*
