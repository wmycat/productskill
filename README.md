# 工具产品机会评估与落地规划

面向独立开发者的 Codex Skill：梳理目标人群、痛点、竞品、核心功能、社媒获客、变现与低成本验证，生成中文产品决策文档。

## 安装与调用

下载本仓库 ZIP，将其中的 `indie-product-discovery` 文件夹放入 `~/.codex/skills/`（如设置了 `CODEX_HOME`，则放入其 `skills/` 目录）。

在新会话中调用：

```text
$indie-product-discovery
我想做一个……，请评估是否值得开发，并输出产品决策文档。
```

未指定市场时，小程序默认国内，App 和网站默认海外；明确指定的市场优先。

[完整使用说明](indie-product-discovery/README.md) · [Skill 指令](indie-product-discovery/SKILL.md)
