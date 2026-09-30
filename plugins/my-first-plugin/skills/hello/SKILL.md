---
name: hello
description: 测试插件自带的问候 skill。当用户说"你好"、"hello"、"测试插件"或想验证插件是否加载成功时使用。会向用户打招呼并报告插件已生效。
---

# Hello Skill

这是一个来自 `my-first-plugin` 测试插件的 skill。

## 行为

当被调用时：

1. 向用户打招呼（可用中文或英文）。
2. 说明当前插件 `my-first-plugin`（版本 1.0.0）已经通过 marketplace 成功加载。
3. 顺带列出插件目录里已包含的内容（如本 skill、plugin.json），帮助用户确认安装结构正确。

## 使用场景

- 首次安装插件后验证加载是否正常。
- 测试 marketplace 的 `plugins/` 目录分发是否生效。
