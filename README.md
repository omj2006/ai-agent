# AI Agent - 多功能AI助手

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![DeepSeek API](https://img.shields.io/badge/DeepSeek-API-4d6bfe?style=flat-square)
![Kling AI](https://img.shields.io/badge/Kling-AI-ff6b6b?style=flat-square)

> 一款基于浏览器的多功能 AI 助手，集成 DeepSeek 大语言模型与可灵 AI 视频生成能力，提供 AI 对话、文本生成、代码辅助、图片风格变换及 AI 视频生成等一站式智能服务。

AI Agent 是一个纯前端单页应用，无需后端服务，打开浏览器即可使用。通过配置 API Key，即可接入 DeepSeek 和可灵 AI 的强大能力，满足日常对话、内容创作、代码编写、图片处理及视频生成等多种需求。

## 在线演示

[https://omj2006.github.io/ai-agent/ai-agent.html](https://omj2006.github.io/ai-agent/ai-agent.html)

## 功能特性

### AI 智能对话
- 基于 DeepSeek 大语言模型的实时对话
- 支持多轮上下文对话
- 流畅的聊天界面体验

### 文本生成
- 文章摘要生成
- 文章扩写
- 创意写作
- 多种文本类型支持

### 代码辅助
- 代码生成
- 代码解释
- 代码优化建议
- 支持多种编程语言

### 图片风格变换
- 图片上传与预览
- 多种风格滤镜选择
- AI 驱动的图像风格迁移（需集成图像生成 API）

### AI 视频生成
- 集成可灵 AI（Kling-V2.6 模型）
- 支持文生视频（Text-to-Video）
- 支持图生视频（Image-to-Video）
- 异步任务轮询与进度显示
- 视频结果在线预览

## 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 | 页面结构 |
| CSS3 | 样式与布局（渐变、动画、响应式） |
| JavaScript (ES6+) | 交互逻辑与 API 调用 |
| DeepSeek API | AI 对话、文本生成、代码辅助 |
| 可灵 AI API | AI 视频生成（Kling-V2.6） |
| GitHub Pages | 静态站点托管 |

## 使用说明

### 快速开始

1. 打开 [在线演示地址](https://omj2006.github.io/ai-agent/ai-agent.html)
2. 在页面顶部的 API 配置区域选择服务提供商
3. 输入对应的 API Key 并保存
4. 即可开始使用各项 AI 功能

### 本地运行

```bash
# 1. 克隆项目
git clone https://github.com/omj2006/ai-agent.git

# 2. 直接在浏览器中打开
open ai-agent.html
# 或使用本地服务器
npx serve .
```

## API 配置说明

### DeepSeek API

DeepSeek 用于 AI 对话、文本生成和代码辅助功能。

| 配置项 | 说明 |
|--------|------|
| API Key | 在 [DeepSeek 开放平台](https://platform.deepseek.com/api_keys) 获取 |
| 用途 | 聊天对话、文本生成、代码辅助 |
| 模型 | deepseek-chat |

### 可灵 AI API

可灵 AI 用于视频生成功能（文生视频 / 图生视频）。

| 配置项 | 说明 |
|--------|------|
| API Key | 在 [可灵 AI 开放平台](https://klingai.com/dev/pricing) 获取 |
| 用途 | 文生视频、图生视频 |
| 模型 | Kling-V2.6 |

> **注意**：API Key 仅保存在浏览器本地（localStorage），不会上传到任何第三方服务器。

## 项目结构

```
ai-agent/
├── ai-agent.html          # 单文件应用（HTML + CSS + JavaScript）
└── README.md              # 项目文档
```

整个项目采用单文件架构，所有 HTML、CSS 和 JavaScript 代码集中在一个 `ai-agent.html` 文件中，便于部署和分享。

## 项目截图

![AI对话](https://img.shields.io/badge/截图-AI对话-blue)
![文本生成](https://img.shields.io/badge/截图-文本生成-green)
![代码辅助](https://img.shields.io/badge/截图-代码辅助-yellow)
![视频生成](https://img.shields.io/badge/截图-视频生成-red)

## 许可证

本项目基于 [MIT License](LICENSE) 开源。
