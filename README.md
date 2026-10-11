# 张天腾 Zhang Tianteng · 业务自动化与 AI 应用 / Business Automation & Applied AI

**张天腾（Zhang Tianteng）**，作品集品牌 **ZTT.** — AI 应用、Agent 与自动化工具开发者，兼品牌策划与内容创作。重庆交通大学广告学本科（2027 届）。
**Zhang Tianteng (ZTT.)** — builds local-first AI applications, agents and automation tools; also works in brand planning and content creation.

- 🌐 个人作品集 / Portfolio：**[zhangtianteng.xyz](https://zhangtianteng.xyz)** — 20 个软件项目、8 份品牌策划提案（DIOR、SHARGE、POP MART 等）、AIGC 影像与音乐作品，附可检索的 AI 助手。
- 📄 经历与项目事实 / Experience & facts：[zhangtianteng.xyz/profile/](https://zhangtianteng.xyz/profile/) · 简历 [zhangtianteng.xyz/downloads/zhangtianteng-resume.pdf](https://zhangtianteng.xyz/downloads/zhangtianteng-resume.pdf)
- 📮 联系 / Contact：994605656tt@gmail.com

本地优先、可离线运行的桌面软件与 AI 工程工具。全部公开项目均可一键克隆运行。
Local-first desktop software and AI engineering tools. Every public repo clones and runs.

## 从真实问题认识我的项目 / Start with the problem

我学广告，也喜欢拍摄、剪辑和调色。现在最投入的是业务自动化：把同事每天重复做的下载、填表、素材整理拆成具体步骤，再做成用得上的工具。

| 想解决的问题 | 项目与完整介绍 |
|---|---|
| 重复下载、匹配、打标和送审 | [达人素材全链路 Agent：流程拆解、工具调用和人工复核](https://zhangtianteng.xyz/software/chameleon-labeling-workflow/) |
| 视频、图文选题缺少灵感 | [TrendScope：热点收集、去重、话题分析与选题](https://zhangtianteng.xyz/software/trendscope/) |
| 多 Agent 怎样从需求推进到交付 | [MAO：执行、验收与失败修复循环](https://zhangtianteng.xyz/software/multi-agent-orchestrator/) |
| 换电脑或换 Agent 后丢失项目上下文 | [ACB：代码状态、交接包与接手说明](https://zhangtianteng.xyz/software/agent-context-bridge/) |
| 本机工具越来越多，缺少统一调用入口 | [WorkflowHub：工具目录、工作流与执行记录](https://zhangtianteng.xyz/software/workflowhub/) |

[先看三个代表项目](https://zhangtianteng.xyz/selected/) · [全部 99 件作品](https://zhangtianteng.xyz/works/) · [关于我](https://zhangtianteng.xyz/about/)

## 🎬 媒体与创作工具 / Media & Creative Tools

| 项目 / Repo | 用途 / What it does |
|---|---|
| [content-trend-analyzer](https://github.com/zhangtt08/content-trend-analyzer) | 内容趋势与选题决策工作台：六平台采集、爆发指数评分、可溯源 AI 选题 / Content trend & topic-selection workbench with evidence-traceable AI topic plans |
| [video-frame-interpolator](https://github.com/zhangtt08/video-frame-interpolator) | 本地视频补帧：30fps → 流畅 60/120fps，保留 10bit/HDR，NVENC 加速 / Offline video frame interpolation, HDR & NVENC |
| [vocal-separator](https://github.com/zhangtt08/vocal-separator) | 本地 AI 音轨分离：人声/鼓/贝斯/其他四轨，Demucs 离线运行 / Local AI stem separation (Demucs), fully offline |
| [stock-media-downloader](https://github.com/zhangtt08/stock-media-downloader) | 素材搜索下载器：聚合 9 个免费图库源，批量下载 / Stock-asset search & batch downloader aggregating 9 free sources |
| [multi-platform-video-downloader](https://github.com/zhangtt08/multi-platform-video-downloader) | 清影下载器：yt-dlp + gallery-dl 双引擎，五平台 Cookie 登录 / Video & image downloader with per-site login sessions |
| [agent-canvas-studio](https://github.com/zhangtt08/agent-canvas-studio) | 面向 AI 智能体的本地图片与排版设计引擎：图层排版、实时预览与多格式导出 / Agent-oriented image & layout design engine with multi-format export |
| [agent-audio-studio](https://github.com/zhangtt08/agent-audio-studio) | 面向 AI 智能体的本地音频工作台：支持音频一键对齐视频时长、人声分离与多轨编辑 / Agent-oriented local audio workspace with auto-alignment & stem separation |
| [local-video-editor](https://github.com/zhangtt08/local-video-editor) | 人和 Agent 共用的本地剪辑软件：Python 剪辑引擎 + HTTP/MCP 接口，界面动作即 Agent 批命令 / Local video editor built for humans AND AI agents |
| [browser-action-recorder](https://github.com/zhangtt08/browser-action-recorder) | 浏览器操作录制 → 可编辑工作流 → 确定性回放 / Record browser actions once, replay deterministically |
| [windows-deep-cleaner](https://github.com/zhangtt08/windows-deep-cleaner) | Windows 深度清理与启动优化，核心区域保护 / Windows maintenance: cleaning, inventory, startup optimization |

## 🤖 AI Agent 工程 / AI Agent Engineering

| 项目 / Repo | 用途 / What it does |
|---|---|
| [local-workflow-hub](https://github.com/zhangtt08/local-workflow-hub) | 本机工具发现与工作流编排中心：扫描整机能力，支持 DAG 可视化编排与 MCP/REST 统一调用 / Local tool catalog & DAG workflow orchestration with MCP/REST interfaces |
| [multi-agent-orchestrator](https://github.com/zhangtt08/multi-agent-orchestrator) | 多 Agent 编排框架：Supervisor/Executor/Reviewer、工作区并发、记忆与回归防护 / Harness-agnostic multi-agent orchestration |
| [ai-project-dashboard](https://github.com/zhangtt08/ai-project-dashboard) | AI 编程项目控制面：真实工程证据、阶段判定、回归与漂移检测 / Control plane aggregating real engineering evidence |
| [ai-agent-task-scheduler](https://github.com/zhangtt08/ai-agent-task-scheduler) | 定时把真实开发任务交给 Codex/Claude Code 执行，内置 MCP 服务器 / Schedule real dev tasks for CLI coding agents, built-in MCP |
| [ai-agent-reliability-lab](https://github.com/zhangtt08/ai-agent-reliability-lab) | AI Agent 动态评测平台：确定性评估器、回归追踪、发布门禁 / Test, evaluate & gate AI agents with deterministic evaluators |
| [agent-code-diagnostic](https://github.com/zhangtt08/agent-code-diagnostic) | Agent 项目静态体检：32 项能力评分 + 文件:行号级建议 / Static audit scoring 32 agent capabilities with file:line evidence |
| [agent-context-handoff](https://github.com/zhangtt08/agent-context-handoff) | 跨机器交接项目上下文：打包-校验-恢复 / Cross-machine project handoff for AI coding agents |
| [job-application-autofill](https://github.com/zhangtt08/job-application-autofill) | 简历自动投填 Edge 扩展：永不自动提交、隐私优先 / Privacy-first job-application autofill (MV3), never auto-submits |
| geo-content-workbench（私有 / private） | GEO/AEO 内容生产与多平台投放工作台 / GEO content production & multi-platform publishing workbench |

## 🌐 站点与个人 / Sites & Personal

- **[zhangtianteng.xyz](https://zhangtianteng.xyz)** — 个人作品集：AI 应用与软件、品牌策划提案、摄影、影像与 AIGC 创作 / Portfolio: AI applications, software, brand proposals, photography and AIGC works
- portfolio-site — 本站源码（私有/private）
- local-knowledge-agent（私有 / private）— 本机个人 Agent / Personal agent on your own machine

---
🌐 优先中文阅读？各公开仓库内均有 `README.zh-CN.md` 完整中文文档。网站与 AI 助手均以张天腾 / Zhang Tianteng 署名。
