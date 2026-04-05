# awesome-design-md 中文指南

> 本仓库 forked 自 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)

## 这是什么

一个 **DESIGN.md 设计系统文件集合**，从 40+ 真实网站提取设计系统。让 AI Coding Agent 能生成像素级匹配的设计。

## 核心理念

| 文件 | 作用 |
|------|------|
| `AGENTS.md` | 告诉 Agent **怎么构建项目** |
| `DESIGN.md` | 告诉 Agent **项目应该长什么样** |

不需要 Figma、不需要 JSON、不需要配置 —— 直接丢 Markdown 文件给 AI Agent，它就能理解你的设计系统。

## 快速开始

### 1. 找一个 DESIGN.md

在仓库中找你喜欢的设计风格，比如：
- `designs/vercel/DESIGN.md` — Vercel 的简约黑白风格
- `designs/stripe/DESIGN.md` — Stripe 的紫渐变优雅
- `designs/linear/DESIGN.md` — Linear 的极简紫色调
- `designs/claude/DESIGN.md` — Claude 的温暖赤陶色

### 2. 复制到项目

```bash
cp designs/vercel/DESIGN.md /your-project/
```

### 3. 让 AI 构建

告诉你的 AI Agent：
> "用这个 DESIGN.md 构建一个 landing page"

## 每个 DESIGN.md 包含什么

| 章节 | 内容 |
|------|------|
| 视觉主题 & 氛围 | 情绪、密度、设计理念 |
| 颜色调色板 | 语义化颜色名 + Hex 值 + 功能角色 |
| 字体规则 | 字体族 + 完整层级表 |
| 组件样式 | 按钮、卡片、输入框、导航的各类状态 |
| 布局原则 | 间距系统、网格、留白哲学 |
| 深度 & 阴影 | 阴影系统、表面层级 |
| Do's and Don'ts | 设计禁忌 |
| 响应式行为 | 断点、触控目标、折叠策略 |
| Agent 提示指南 | 快速颜色参考 |

## 品牌合集

### AI & 机器学习
Claude, Cohere, ElevenLabs, Minimax, Mistral AI, Ollama, xAI...

### 开发者工具
Cursor, Linear, Vercel, Stripe, Supabase, Raycast, Warp, Expo, Mintlify...

### 企业品牌
Apple, NVIDIA, SpaceX, Spotify, Uber, Airbnb, BMW, IBM...

### 金融 & 加密
Coinbase, Kraken, Revolut, Wise...

## 如何使用 Claude Code / Cursor / Copilot

1. 克隆你需要的 DESIGN.md 到项目根目录
2. 在 AI Agent 中引用它：
   ```
   请参考 DESIGN.md 中的设计规范来构建这个页面
   ```
3. 获得像素级匹配的设计！

## 本地预览

每个设计文件夹包含：
- `DESIGN.md` — 设计系统文档
- `preview.html` — 视觉目录（亮色）
- `preview-dark.html` — 暗色版本

## 示例项目结构

```
my-project/
├── DESIGN.md          ← 从这里复制
├── src/
│   └── components/
└── package.json
```

## 相关资源

- [Google Stitch](https://stitch.google/) — 原始设计工具
- [VoltAgent](https://voltagent.ai/) — AI Agent 框架
- [Claude](https://claude.ai/) — Anthropic AI 助手

## License

MIT License

---

**原作者**: [VoltAgent](https://github.com/VoltAgent)  
**本仓库**: fork 自 [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md)
