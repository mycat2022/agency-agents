# 🎭 The Agency: AI Specialists Ready to Transform Your Workflow
# 🎭 The Agency: 随时为您改变工作流程的AI专家团队

> **A complete AI agency at your fingertips** - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.
> **一个完整的AI代理机构尽在您的指尖** - 从前端高手到Reddit社区忍者，从趣味注入者到现实检验者。每个智能体都是具有个性、流程和成熟交付成果的专业专家。

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 What Is This? / 这是什么？

Born from a Reddit thread and months of iteration, **The Agency** is a growing collection of meticulously crafted AI agent personalities. Each agent is:

诞生于Reddit上的一个讨论帖，并经过数月的迭代完善，**The Agency** 是一个不断增长的精心打造的AI智能体个性集合。每个智能体都具备：

- **🎯 Specialized / 专业化**: Deep expertise in their domain (not generic prompt templates) / 在其领域拥有深厚的专业知识（不是通用的提示模板）
- **🧠 Personality-Driven / 个性驱动**: Unique voice, communication style, and approach / 独特的声音、沟通风格和方法
- **📋 Deliverable-Focused / 以交付为导向**: Real code, processes, and measurable outcomes / 真实的代码、流程和可衡量的成果
- **✅ Production-Ready / 生产就绪**: Battle-tested workflows and success metrics / 经过实战检验的工作流程和成功指标

**Think of it as**: Assembling your dream team, except they're AI specialists who never sleep, never complain, and always deliver.

**可以这样理解**：组建您的梦之队，只不过他们是永不休息、从不抱怨、始终交付的AI专家。

---

## ⚡ Quick Start / 快速开始

### Option 1: Use with Claude Code (Recommended) / 选项1：与Claude Code一起使用（推荐）

```bash
# Install all agents to your Claude Code directory / 将所有智能体安装到您的Claude Code目录
./scripts/install.sh --tool claude-code

# Or manually copy a category if you only want one division / 如果只需要一个部门，可以手动复制一个类别
cp engineering/*.md ~/.claude/agents/

# Then activate any agent in your Claude Code sessions: / 然后在Claude Code会话中激活任意智能体：
# "Hey Claude, activate Frontend Developer mode and help me build a React component"
# "嘿Claude，激活前端开发者模式并帮我构建一个React组件"
```

### Option 2: Use as Reference / 选项2：作为参考使用

Each agent file contains: / 每个智能体文件包含：
- Identity & personality traits / 身份与个性特征
- Core mission & workflows / 核心使命与工作流程
- Technical deliverables with code examples / 带有代码示例的技术交付成果
- Success metrics & communication style / 成功指标与沟通风格

Browse the agents below and copy/adapt the ones you need!
浏览下方的智能体列表，复制或调整您需要的！

### Option 3: Use with Other Tools / 选项3：与其他工具一起使用

(GitHub Copilot, Antigravity, Gemini CLI, OpenCode, OpenClaw, Cursor, Aider, Windsurf, Kimi Code)

```bash
# Step 1 -- generate integration files for all supported tools / 第1步 -- 为所有支持的工具生成集成文件
./scripts/convert.sh

# Step 2 -- install interactively (auto-detects what you have installed) / 第2步 -- 交互式安装（自动检测已安装的工具）
./scripts/install.sh

# Or target a specific tool directly / 或直接针对特定工具
./scripts/install.sh --tool antigravity
./scripts/install.sh --tool gemini-cli
./scripts/install.sh --tool opencode
./scripts/install.sh --tool copilot
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool cursor
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool kimi
```

See the [Multi-Tool Integrations](#-multi-tool-integrations) section below for full details.
有关完整详情，请参阅下方的[多工具集成](#-multi-tool-integrations)部分。

---

## 🎨 The Agency Roster / 机构名册

### 💻 Engineering Division / 工程部门

Building the future, one commit at a time. / 一次提交，一次构建未来。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎨 [Frontend Developer / 前端开发者](engineering/engineering-frontend-developer.md) | React/Vue/Angular, UI implementation, performance / React/Vue/Angular、UI实现、性能优化 | Modern web apps, pixel-perfect UIs, Core Web Vitals optimization / 现代Web应用、像素级完美的UI、Core Web Vitals优化 |
| 🏗️ [Backend Architect / 后端架构师](engineering/engineering-backend-architect.md) | API design, database architecture, scalability / API设计、数据库架构、可扩展性 | Server-side systems, microservices, cloud infrastructure / 服务端系统、微服务、云基础设施 |
| 📱 [Mobile App Builder / 移动应用构建者](engineering/engineering-mobile-app-builder.md) | iOS/Android, React Native, Flutter / iOS/Android、React Native、Flutter | Native and cross-platform mobile applications / 原生和跨平台移动应用 |
| 🤖 [AI Engineer / AI工程师](engineering/engineering-ai-engineer.md) | ML models, deployment, AI integration / 机器学习模型、部署、AI集成 | Machine learning features, data pipelines, AI-powered apps / 机器学习功能、数据管道、AI驱动应用 |
| 🚀 [DevOps Automator / DevOps自动化工程师](engineering/engineering-devops-automator.md) | CI/CD, infrastructure automation, cloud ops / CI/CD、基础设施自动化、云运维 | Pipeline development, deployment automation, monitoring / 管道开发、部署自动化、监控 |
| ⚡ [Rapid Prototyper / 快速原型师](engineering/engineering-rapid-prototyper.md) | Fast POC development, MVPs / 快速POC开发、MVP | Quick proof-of-concepts, hackathon projects, fast iteration / 快速概念验证、黑客马拉松项目、快速迭代 |
| 💎 [Senior Developer / 高级开发者](engineering/engineering-senior-developer.md) | Laravel/Livewire, advanced patterns / Laravel/Livewire、高级模式 | Complex implementations, architecture decisions / 复杂实现、架构决策 |
| 🔧 [Filament Optimization Specialist / Filament优化专家](engineering/engineering-filament-optimization-specialist.md) | Filament PHP admin UX, structural form redesign, resource optimization / Filament PHP管理后台UX、表单结构重设计、资源优化 | Restructuring Filament resources/forms/tables for faster, cleaner admin workflows / 重构Filament资源/表单/表格以实现更快、更简洁的管理工作流程 |
| 🔒 [Security Engineer / 安全工程师](engineering/engineering-security-engineer.md) | Threat modeling, secure code review, security architecture / 威胁建模、安全代码审查、安全架构 | Application security, vulnerability assessment, security CI/CD / 应用安全、漏洞评估、安全CI/CD |
| ⚡ [Autonomous Optimization Architect / 自主优化架构师](engineering/engineering-autonomous-optimization-architect.md) | LLM routing, cost optimization, shadow testing / LLM路由、成本优化、影子测试 | Autonomous systems needing intelligent API selection and cost guardrails / 需要智能API选择和成本护栏的自主系统 |
| 🔩 [Embedded Firmware Engineer / 嵌入式固件工程师](engineering/engineering-embedded-firmware-engineer.md) | Bare-metal, RTOS, ESP32/STM32/Nordic firmware / 裸机、RTOS、ESP32/STM32/Nordic固件 | Production-grade embedded systems and IoT devices / 生产级嵌入式系统和物联网设备 |
| 🚨 [Incident Response Commander / 事件响应指挥官](engineering/engineering-incident-response-commander.md) | Incident management, post-mortems, on-call / 事件管理、事后分析、值班 | Managing production incidents and building incident readiness / 管理生产事件并建立事件响应准备 |
| ⛓️ [Solidity Smart Contract Engineer / Solidity智能合约工程师](engineering/engineering-solidity-smart-contract-engineer.md) | EVM contracts, gas optimization, DeFi / EVM合约、Gas优化、DeFi | Secure, gas-optimized smart contracts and DeFi protocols / 安全、Gas优化的智能合约和DeFi协议 |
| 🧭 [Codebase Onboarding Engineer / 代码库入门工程师](engineering/engineering-codebase-onboarding-engineer.md) | Fast developer onboarding, read-only codebase exploration, factual explanation / 快速开发者入门、只读代码库探索、事实性解释 | Helping new developers understand unfamiliar repos quickly by reading the code, tracing code paths, and stating facts about structure and behavior / 通过阅读代码、追踪代码路径并陈述结构和行为的事实，帮助新开发者快速理解不熟悉的仓库 |
| 📚 [Technical Writer / 技术文档撰写者](engineering/engineering-technical-writer.md) | Developer docs, API reference, tutorials / 开发者文档、API参考、教程 | Clear, accurate technical documentation / 清晰、准确的技术文档 |
| 🎯 [Threat Detection Engineer / 威胁检测工程师](engineering/engineering-threat-detection-engineer.md) | SIEM rules, threat hunting, ATT&CK mapping / SIEM规则、威胁狩猎、ATT&CK映射 | Building detection layers and threat hunting / 构建检测层和威胁狩猎 |
| 💬 [WeChat Mini Program Developer / 微信小程序开发者](engineering/engineering-wechat-mini-program-developer.md) | WeChat ecosystem, Mini Programs, payment integration / 微信生态、小程序、支付集成 | Building performant apps for the WeChat ecosystem / 为微信生态系统构建高性能应用 |
| 👁️ [Code Reviewer / 代码审查者](engineering/engineering-code-reviewer.md) | Constructive code review, security, maintainability / 建设性代码审查、安全、可维护性 | PR reviews, code quality gates, mentoring through review / PR审查、代码质量门禁、通过审查进行指导 |
| 🗄️ [Database Optimizer / 数据库优化师](engineering/engineering-database-optimizer.md) | Schema design, query optimization, indexing strategies / 模式设计、查询优化、索引策略 | PostgreSQL/MySQL tuning, slow query debugging, migration planning / PostgreSQL/MySQL调优、慢查询调试、迁移规划 |
| 🌿 [Git Workflow Master / Git工作流大师](engineering/engineering-git-workflow-master.md) | Branching strategies, conventional commits, advanced Git / 分支策略、约定式提交、高级Git | Git workflow design, history cleanup, CI-friendly branch management / Git工作流设计、历史清理、CI友好的分支管理 |
| 🏛️ [Software Architect / 软件架构师](engineering/engineering-software-architect.md) | System design, DDD, architectural patterns, trade-off analysis / 系统设计、领域驱动设计、架构模式、权衡分析 | Architecture decisions, domain modeling, system evolution strategy / 架构决策、领域建模、系统演进策略 |
| 🛡️ [SRE / 站点可靠性工程师](engineering/engineering-sre.md) | SLOs, error budgets, observability, chaos engineering / SLO、错误预算、可观测性、混沌工程 | Production reliability, toil reduction, capacity planning / 生产可靠性、减少重复性工作、容量规划 |
| 🧬 [AI Data Remediation Engineer / AI数据修复工程师](engineering/engineering-ai-data-remediation-engineer.md) | Self-healing pipelines, air-gapped SLMs, semantic clustering / 自修复管道、气隙SLM、语义聚类 | Fixing broken data at scale with zero data loss / 以零数据丢失大规模修复损坏的数据 |
| 🔧 [Data Engineer / 数据工程师](engineering/engineering-data-engineer.md) | Data pipelines, lakehouse architecture, ETL/ELT / 数据管道、湖仓架构、ETL/ELT | Building reliable data infrastructure and warehousing / 构建可靠的数据基础设施和仓储 |
| 🔗 [Feishu Integration Developer / 飞书集成开发者](engineering/engineering-feishu-integration-developer.md) | Feishu/Lark Open Platform, bots, workflows / 飞书/Lark开放平台、机器人、工作流 | Building integrations for the Feishu ecosystem / 为飞书生态系统构建集成 |
| 🧱 [CMS Developer / CMS开发者](engineering/engineering-cms-developer.md) | WordPress & Drupal themes, plugins/modules, content architecture / WordPress和Drupal主题、插件/模块、内容架构 | Code-first CMS implementation and customization / 代码优先的CMS实现和定制 |
| 📧 [Email Intelligence Engineer / 邮件智能工程师](engineering/engineering-email-intelligence-engineer.md) | Email parsing, MIME extraction, structured data for AI agents / 邮件解析、MIME提取、AI智能体的结构化数据 | Turning raw email threads into reasoning-ready context / 将原始邮件线程转换为可供推理的上下文 |
| 🎙️ [Voice AI Integration Engineer / 语音AI集成工程师](engineering/engineering-voice-ai-integration-engineer.md) | Speech-to-text pipelines, Whisper, ASR, speaker diarization / 语音转文本管道、Whisper、ASR、说话人分离 | End-to-end transcription pipelines, audio preprocessing, structured transcript delivery / 端到端转录管道、音频预处理、结构化转录交付 |

### 🎨 Design Division / 设计部门

Making it beautiful, usable, and delightful. / 让它美观、易用、令人愉悦。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎯 [UI Designer / UI设计师](design/design-ui-designer.md) | Visual design, component libraries, design systems / 视觉设计、组件库、设计系统 | Interface creation, brand consistency, component design / 界面创建、品牌一致性、组件设计 |
| 🔍 [UX Researcher / UX研究员](design/design-ux-researcher.md) | User testing, behavior analysis, research / 用户测试、行为分析、研究 | Understanding users, usability testing, design insights / 理解用户、可用性测试、设计洞察 |
| 🏛️ [UX Architect / UX架构师](design/design-ux-architect.md) | Technical architecture, CSS systems, implementation / 技术架构、CSS系统、实现 | Developer-friendly foundations, implementation guidance / 开发者友好的基础、实现指导 |
| 🎭 [Brand Guardian / 品牌守护者](design/design-brand-guardian.md) | Brand identity, consistency, positioning / 品牌识别、一致性、定位 | Brand strategy, identity development, guidelines / 品牌战略、识别开发、指南 |
| 📖 [Visual Storyteller / 视觉叙事者](design/design-visual-storyteller.md) | Visual narratives, multimedia content / 视觉叙事、多媒体内容 | Compelling visual stories, brand storytelling / 引人入胜的视觉故事、品牌叙事 |
| ✨ [Whimsy Injector / 趣味注入者](design/design-whimsy-injector.md) | Personality, delight, playful interactions / 个性、愉悦、趣味交互 | Adding joy, micro-interactions, Easter eggs, brand personality / 增添乐趣、微交互、彩蛋、品牌个性 |
| 📷 [Image Prompt Engineer / 图像提示工程师](design/design-image-prompt-engineer.md) | AI image generation prompts, photography / AI图像生成提示、摄影 | Photography prompts for Midjourney, DALL-E, Stable Diffusion / Midjourney、DALL-E、Stable Diffusion的摄影提示 |
| 🌈 [Inclusive Visuals Specialist / 包容性视觉专家](design/design-inclusive-visuals-specialist.md) | Representation, bias mitigation, authentic imagery / 代表性、偏见缓解、真实图像 | Generating culturally accurate AI images and video / 生成文化准确的AI图像和视频 |

### 💰 Paid Media Division / 付费媒体部门

Turning ad spend into measurable business outcomes. / 将广告支出转化为可衡量的业务成果。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
| --- | --- | --- |
| 💰 [PPC Campaign Strategist / PPC活动策略师](paid-media/paid-media-ppc-strategist.md) | Google/Microsoft/Amazon Ads, account architecture, bidding / Google/Microsoft/Amazon广告、账户架构、竞价 | Account buildouts, budget allocation, scaling, performance diagnosis / 账户搭建、预算分配、扩展、性能诊断 |
| 🔍 [Search Query Analyst / 搜索查询分析师](paid-media/paid-media-search-query-analyst.md) | Search term analysis, negative keywords, intent mapping / 搜索词分析、否定关键词、意图映射 | Query audits, wasted spend elimination, keyword discovery / 查询审计、消除浪费支出、关键词发现 |
| 📋 [Paid Media Auditor / 付费媒体审计师](paid-media/paid-media-auditor.md) | 200+ point account audits, competitive analysis / 200+点账户审计、竞争分析 | Account takeovers, quarterly reviews, competitive pitches / 账户接管、季度审查、竞争提案 |
| 📡 [Tracking & Measurement Specialist / 追踪与测量专家](paid-media/paid-media-tracking-specialist.md) | GTM, GA4, conversion tracking, CAPI / GTM、GA4、转化追踪、CAPI | New implementations, tracking audits, platform migrations / 新实施、追踪审计、平台迁移 |
| ✍️ [Ad Creative Strategist / 广告创意策略师](paid-media/paid-media-creative-strategist.md) | RSA copy, Meta creative, Performance Max assets / RSA文案、Meta创意、Performance Max素材 | Creative launches, testing programs, ad fatigue refreshes / 创意发布、测试计划、广告疲劳刷新 |
| 📺 [Programmatic & Display Buyer / 程序化与展示买家](paid-media/paid-media-programmatic-buyer.md) | GDN, DSPs, partner media, ABM display / GDN、DSP、合作伙伴媒体、ABM展示 | Display planning, partner outreach, ABM programs / 展示规划、合作伙伴拓展、ABM计划 |
| 📱 [Paid Social Strategist / 付费社交策略师](paid-media/paid-media-paid-social-strategist.md) | Meta, LinkedIn, TikTok, cross-platform social / Meta、LinkedIn、TikTok、跨平台社交 | Social ad programs, platform selection, audience strategy / 社交广告计划、平台选择、受众策略 |

### 💼 Sales Division / 销售部门

Turning pipeline into revenue through craft, not CRM busywork. / 通过技艺而非CRM琐事将销售管道转化为收入。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎯 [Outbound Strategist / 外联策略师](sales/sales-outbound-strategist.md) | Signal-based prospecting, multi-channel sequences, ICP targeting / 基于信号的潜在客户开发、多渠道序列、ICP定位 | Building pipeline through research-driven outreach, not volume / 通过研究驱动的外联而非数量来构建管道 |
| 🔍 [Discovery Coach / 发现教练](sales/sales-discovery-coach.md) | SPIN, Gap Selling, Sandler — question design and call structure / SPIN、Gap Selling、Sandler — 问题设计和通话结构 | Preparing for discovery calls, qualifying opportunities, coaching reps / 准备发现电话、评估机会、指导销售代表 |
| ♟️ [Deal Strategist / 交易策略师](sales/sales-deal-strategist.md) | MEDDPICC qualification, competitive positioning, win planning / MEDDPICC资格评估、竞争定位、赢单规划 | Scoring deals, exposing pipeline risk, building win strategies / 交易评分、暴露管道风险、构建赢单策略 |
| 🛠️ [Sales Engineer / 销售工程师](sales/sales-engineer.md) | Technical demos, POC scoping, competitive battlecards / 技术演示、POC范围、竞争战卡 | Pre-sales technical wins, demo prep, competitive positioning / 售前技术胜利、演示准备、竞争定位 |
| 🏹 [Proposal Strategist / 提案策略师](sales/sales-proposal-strategist.md) | RFP response, win themes, narrative structure / RFP响应、赢单主题、叙事结构 | Writing proposals that persuade, not just comply / 撰写说服性的提案，而非仅仅合规 |
| 📊 [Pipeline Analyst / 管道分析师](sales/sales-pipeline-analyst.md) | Forecasting, pipeline health, deal velocity, RevOps / 预测、管道健康、交易速度、RevOps | Pipeline reviews, forecast accuracy, revenue operations / 管道审查、预测准确性、收入运营 |
| 🗺️ [Account Strategist / 客户策略师](sales/sales-account-strategist.md) | Land-and-expand, QBRs, stakeholder mapping / 落地与扩展、季度业务审查、利益相关者映射 | Post-sale expansion, account planning, NRR growth / 售后扩展、客户规划、净收入留存增长 |
| 🏋️ [Sales Coach / 销售教练](sales/sales-coach.md) | Rep development, call coaching, pipeline review facilitation / 销售代表发展、通话指导、管道审查协调 | Making every rep and every deal better through structured coaching / 通过结构化指导让每个代表和每笔交易变得更好 |
| 🎯 [Sales Outreach / 销售外联](specialized/sales-outreach.md) | Cold prospecting, multi-touch cadences, objection handling, proposals / 冷潜在客户开发、多触点节奏、异议处理、提案 | Top-of-funnel B2B outreach — from cold email to booked discovery call / 漏斗顶部的B2B外联 — 从冷邮件到预约发现电话 |

### 📢 Marketing Division / 市场部门

Growing your audience, one authentic interaction at a time. / 一次真实的互动，一次增长您的受众。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🚀 [Growth Hacker / 增长黑客](marketing/marketing-growth-hacker.md) | Rapid user acquisition, viral loops, experiments / 快速用户获取、病毒循环、实验 | Explosive growth, user acquisition, conversion optimization / 爆发式增长、用户获取、转化优化 |
| 📝 [Content Creator / 内容创作者](marketing/marketing-content-creator.md) | Multi-platform content, editorial calendars / 多平台内容、编辑日历 | Content strategy, copywriting, brand storytelling / 内容策略、文案、品牌叙事 |
| 🐦 [Twitter Engager / Twitter互动专家](marketing/marketing-twitter-engager.md) | Real-time engagement, thought leadership / 实时互动、思想领导力 | Twitter strategy, LinkedIn campaigns, professional social / Twitter策略、LinkedIn活动、专业社交 |
| 📱 [TikTok Strategist / TikTok策略师](marketing/marketing-tiktok-strategist.md) | Viral content, algorithm optimization / 病毒内容、算法优化 | TikTok growth, viral content, Gen Z/Millennial audience / TikTok增长、病毒内容、Z世代/千禧一代受众 |
| 📸 [Instagram Curator / Instagram策展人](marketing/marketing-instagram-curator.md) | Visual storytelling, community building / 视觉叙事、社区建设 | Instagram strategy, aesthetic development, visual content / Instagram策略、美学发展、视觉内容 |
| 🤝 [Reddit Community Builder / Reddit社区建设者](marketing/marketing-reddit-community-builder.md) | Authentic engagement, value-driven content / 真实互动、价值驱动内容 | Reddit strategy, community trust, authentic marketing / Reddit策略、社区信任、真实营销 |
| 📱 [App Store Optimizer / 应用商店优化师](marketing/marketing-app-store-optimizer.md) | ASO, conversion optimization, discoverability / ASO、转化优化、可发现性 | App marketing, store optimization, app growth / 应用营销、商店优化、应用增长 |
| 🌐 [Social Media Strategist / 社交媒体策略师](marketing/marketing-social-media-strategist.md) | Cross-platform strategy, campaigns / 跨平台策略、活动 | Overall social strategy, multi-platform campaigns / 整体社交策略、多平台活动 |
| 📕 [Xiaohongshu Specialist / 小红书专家](marketing/marketing-xiaohongshu-specialist.md) | Lifestyle content, trend-driven strategy / 生活方式内容、趋势驱动策略 | Xiaohongshu growth, aesthetic storytelling, Gen Z audience / 小红书增长、美学叙事、Z世代受众 |
| 💬 [WeChat Official Account Manager / 微信公众号运营](marketing/marketing-wechat-official-account.md) | Subscriber engagement, content marketing / 订阅者互动、内容营销 | WeChat OA strategy, community building, conversion optimization / 微信公众号策略、社区建设、转化优化 |
| 🧠 [Zhihu Strategist / 知乎策略师](marketing/marketing-zhihu-strategist.md) | Thought leadership, knowledge-driven engagement / 思想领导力、知识驱动互动 | Zhihu authority building, Q&A strategy, lead generation / 知乎权威建设、问答策略、潜在客户生成 |
| 🇨🇳 [Baidu SEO Specialist / 百度SEO专家](marketing/marketing-baidu-seo-specialist.md) | Baidu optimization, China SEO, ICP compliance / 百度优化、中国SEO、ICP合规 | Ranking in Baidu and reaching China's search market / 在百度排名并触达中国搜索市场 |
| 🎬 [Bilibili Content Strategist / Bilibili内容策略师](marketing/marketing-bilibili-content-strategist.md) | B站 algorithm, danmaku culture, UP主 growth / B站算法、弹幕文化、UP主增长 | Building audiences on Bilibili with community-first content / 以社区优先的内容在Bilibili上建立受众 |
| 🎠 [Carousel Growth Engine / 轮播增长引擎](marketing/marketing-carousel-growth-engine.md) | TikTok/Instagram carousels, autonomous publishing / TikTok/Instagram轮播、自动发布 | Generating and publishing viral carousel content / 生成和发布病毒式轮播内容 |
| 💼 [LinkedIn Content Creator / LinkedIn内容创作者](marketing/marketing-linkedin-content-creator.md) | Personal branding, thought leadership, professional content / 个人品牌、思想领导力、专业内容 | LinkedIn growth, professional audience building, B2B content / LinkedIn增长、专业受众建设、B2B内容 |
| 🛒 [China E-Commerce Operator / 中国电商运营](marketing/marketing-china-ecommerce-operator.md) | Taobao, Tmall, Pinduoduo, live commerce / 淘宝、天猫、拼多多、直播电商 | Running multi-platform e-commerce in China / 在中国运营多平台电商 |
| 🎥 [Kuaishou Strategist / 快手策略师](marketing/marketing-kuaishou-strategist.md) | Kuaishou, 老铁 community, grassroots growth / 快手、老铁社区、草根增长 | Building authentic audiences in lower-tier markets / 在低线城市建立真实受众 |
| 🔍 [SEO Specialist / SEO专家](marketing/marketing-seo-specialist.md) | Technical SEO, content strategy, link building / 技术SEO、内容策略、链接建设 | Driving sustainable organic search growth / 推动可持续的有机搜索增长 |
| 📘 [Book Co-Author / 书籍合著者](marketing/marketing-book-co-author.md) | Thought-leadership books, ghostwriting, publishing / 思想领导力书籍、代笔、出版 | Strategic book collaboration for founders and experts / 为创始人和专家提供战略性书籍合作 |
| 🌏 [Cross-Border E-Commerce Specialist / 跨境电商专家](marketing/marketing-cross-border-ecommerce.md) | Amazon, Shopee, Lazada, cross-border fulfillment / Amazon、Shopee、Lazada、跨境履约 | Full-funnel cross-border e-commerce strategy / 全漏斗跨境电商策略 |
| 🎵 [Douyin Strategist / 抖音策略师](marketing/marketing-douyin-strategist.md) | Douyin platform, short-video marketing, algorithm / 抖音平台、短视频营销、算法 | Growing audiences on China's leading short-video platform / 在中国领先的短视频平台上增长受众 |
| 🎙️ [Livestream Commerce Coach / 直播电商教练](marketing/marketing-livestream-commerce-coach.md) | Host training, live room optimization, conversion / 主播培训、直播间优化、转化 | Building high-performing livestream e-commerce operations / 构建高性能直播电商运营 |
| 🎧 [Podcast Strategist / 播客策略师](marketing/marketing-podcast-strategist.md) | Podcast content strategy, platform optimization / 播客内容策略、平台优化 | Chinese podcast market strategy and operations / 中文播客市场策略和运营 |
| 🔒 [Private Domain Operator / 私域运营](marketing/marketing-private-domain-operator.md) | WeCom, private traffic, community operations / 企业微信、私域流量、社区运营 | Building enterprise WeChat private domain ecosystems / 构建企业微信私域生态系统 |
| 🎬 [Short-Video Editing Coach / 短视频剪辑教练](marketing/marketing-short-video-editing-coach.md) | Post-production, editing workflows, platform specs / 后期制作、剪辑工作流、平台规格 | Hands-on short-video editing training and optimization / 实践性短视频剪辑培训和优化 |
| 🔥 [Weibo Strategist / 微博策略师](marketing/marketing-weibo-strategist.md) | Sina Weibo, trending topics, fan engagement / 新浪微博、热门话题、粉丝互动 | Full-spectrum Weibo operations and growth / 全谱微博运营和增长 |
| 🔮 [AI Citation Strategist / AI引用策略师](marketing/marketing-ai-citation-strategist.md) | AEO/GEO, AI recommendation visibility, citation auditing / AEO/GEO、AI推荐可见性、引用审计 | Improving brand visibility across ChatGPT, Claude, Gemini, Perplexity / 提高在ChatGPT、Claude、Gemini、Perplexity上的品牌可见性 |
| 🇨🇳 [China Market Localization Strategist / 中国市场本地化策略师](marketing/marketing-china-market-localization-strategist.md) | Full-stack China market localization, Douyin/Xiaohongshu/WeChat GTM / 全栈中国市场本地化、抖音/小红书/微信GTM | Turning trend signals into executable China go-to-market strategies / 将趋势信号转化为可执行的中国市场进入策略 |
| 🎬 [Video Optimization Specialist / 视频优化专家](marketing/marketing-video-optimization-specialist.md) | YouTube algorithm strategy, chaptering, thumbnail concepts / YouTube算法策略、章节、缩略图概念 | YouTube channel growth, video SEO, audience retention optimization / YouTube频道增长、视频SEO、受众留存优化 |

### 📊 Product Division / 产品部门

Building the right thing at the right time. / 在正确的时间构建正确的产品。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎯 [Sprint Prioritizer / 冲刺优先级排序师](product/product-sprint-prioritizer.md) | Agile planning, feature prioritization / 敏捷规划、功能优先级排序 | Sprint planning, resource allocation, backlog management / 冲刺规划、资源分配、待办事项管理 |
| 🔍 [Trend Researcher / 趋势研究员](product/product-trend-researcher.md) | Market intelligence, competitive analysis / 市场情报、竞争分析 | Market research, opportunity assessment, trend identification / 市场研究、机会评估、趋势识别 |
| 💬 [Feedback Synthesizer / 反馈综合师](product/product-feedback-synthesizer.md) | User feedback analysis, insights extraction / 用户反馈分析、洞察提取 | Feedback analysis, user insights, product priorities / 反馈分析、用户洞察、产品优先级 |
| 🧠 [Behavioral Nudge Engine / 行为助推引擎](product/product-behavioral-nudge-engine.md) | Behavioral psychology, nudge design, engagement / 行为心理学、助推设计、互动 | Maximizing user motivation through behavioral science / 通过行为科学最大化用户动机 |
| 🧭 [Product Manager / 产品经理](product/product-manager.md) | Full lifecycle product ownership / 全生命周期产品所有权 | Discovery, PRDs, roadmap planning, GTM, outcome measurement / 发现、PRD、路线图规划、GTM、成果衡量 |

### 🎬 Project Management Division / 项目管理部门

Keeping the trains running on time (and under budget). / 确保列车准时运行（并在预算内）。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎬 [Studio Producer / 工作室制作人](project-management/project-management-studio-producer.md) | High-level orchestration, portfolio management / 高级编排、组合管理 | Multi-project oversight, strategic alignment, resource allocation / 多项目监督、战略对齐、资源分配 |
| 🐑 [Project Shepherd / 项目牧羊人](project-management/project-management-project-shepherd.md) | Cross-functional coordination, timeline management / 跨职能协调、时间线管理 | End-to-end project coordination, stakeholder management / 端到端项目协调、利益相关者管理 |
| ⚙️ [Studio Operations / 工作室运营](project-management/project-management-studio-operations.md) | Day-to-day efficiency, process optimization / 日常效率、流程优化 | Operational excellence, team support, productivity / 运营卓越、团队支持、生产力 |
| 🧪 [Experiment Tracker / 实验追踪器](project-management/project-management-experiment-tracker.md) | A/B tests, hypothesis validation / A/B测试、假设验证 | Experiment management, data-driven decisions, testing / 实验管理、数据驱动决策、测试 |
| 👔 [Senior Project Manager / 高级项目经理](project-management/project-manager-senior.md) | Realistic scoping, task conversion / 现实范围界定、任务转换 | Converting specs to tasks, scope management / 将规格转换为任务、范围管理 |
| 📋 [Jira Workflow Steward / Jira工作流管理员](project-management/project-management-jira-workflow-steward.md) | Git workflow, branch strategy, traceability / Git工作流、分支策略、可追溯性 | Enforcing Jira-linked Git discipline and delivery / 强制执行Jira关联的Git纪律和交付 |

### 🧪 Testing Division / 测试部门

Breaking things so users don't have to. / 破坏东西，这样用户就不必了。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 📸 [Evidence Collector / 证据收集者](testing/testing-evidence-collector.md) | Screenshot-based QA, visual proof / 基于截图的QA、视觉证明 | UI testing, visual verification, bug documentation / UI测试、视觉验证、Bug文档 |
| 🔍 [Reality Checker / 现实检验者](testing/testing-reality-checker.md) | Evidence-based certification, quality gates / 基于证据的认证、质量门禁 | Production readiness, quality approval, release certification / 生产就绪、质量批准、发布认证 |
| 📊 [Test Results Analyzer / 测试结果分析器](testing/testing-test-results-analyzer.md) | Test evaluation, metrics analysis / 测试评估、指标分析 | Test output analysis, quality insights, coverage reporting / 测试输出分析、质量洞察、覆盖率报告 |
| ⚡ [Performance Benchmarker / 性能基准测试师](testing/testing-performance-benchmarker.md) | Performance testing, optimization / 性能测试、优化 | Speed testing, load testing, performance tuning / 速度测试、负载测试、性能调优 |
| 🔌 [API Tester / API测试师](testing/testing-api-tester.md) | API validation, integration testing / API验证、集成测试 | API testing, endpoint verification, integration QA / API测试、端点验证、集成QA |
| 🛠️ [Tool Evaluator / 工具评估师](testing/testing-tool-evaluator.md) | Technology assessment, tool selection / 技术评估、工具选择 | Evaluating tools, software recommendations, tech decisions / 评估工具、软件推荐、技术决策 |
| 🔄 [Workflow Optimizer / 工作流优化师](testing/testing-workflow-optimizer.md) | Process analysis, workflow improvement / 流程分析、工作流改进 | Process optimization, efficiency gains, automation opportunities / 流程优化、效率提升、自动化机会 |
| ♿ [Accessibility Auditor / 可访问性审计师](testing/testing-accessibility-auditor.md) | WCAG auditing, assistive technology testing / WCAG审计、辅助技术测试 | Accessibility compliance, screen reader testing, inclusive design verification / 可访问性合规、屏幕阅读器测试、包容性设计验证 |

### 🛟 Support Division / 支持部门

The backbone of the operation. / 运营的支柱。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 💬 [Support Responder / 支持响应者](support/support-support-responder.md) | Customer service, issue resolution / 客户服务、问题解决 | Customer support, user experience, support operations / 客户支持、用户体验、支持运营 |
| 📊 [Analytics Reporter / 分析报告员](support/support-analytics-reporter.md) | Data analysis, dashboards, insights / 数据分析、仪表板、洞察 | Business intelligence, KPI tracking, data visualization / 商业智能、KPI追踪、数据可视化 |
| 💰 [Finance Tracker / 财务追踪者](support/support-finance-tracker.md) | Financial planning, budget management / 财务规划、预算管理 | Financial analysis, cash flow, business performance / 财务分析、现金流、业务绩效 |
| 🏗️ [Infrastructure Maintainer / 基础设施维护者](support/support-infrastructure-maintainer.md) | System reliability, performance optimization / 系统可靠性、性能优化 | Infrastructure management, system operations, monitoring / 基础设施管理、系统运营、监控 |
| ⚖️ [Legal Compliance Checker / 法律合规检查员](support/support-legal-compliance-checker.md) | Compliance, regulations, legal review / 合规、法规、法律审查 | Legal compliance, regulatory requirements, risk management / 法律合规、监管要求、风险管理 |
| 📑 [Executive Summary Generator / 执行摘要生成器](support/support-executive-summary-generator.md) | C-suite communication, strategic summaries / C级沟通、战略摘要 | Executive reporting, strategic communication, decision support / 高管报告、战略沟通、决策支持 |

### 🥽 Spatial Computing Division / 空间计算部门

Building the immersive future. / 构建沉浸式未来。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🏗️ [XR Interface Architect / XR界面架构师](spatial-computing/xr-interface-architect.md) | Spatial interaction design, immersive UX / 空间交互设计、沉浸式UX | AR/VR/XR interface design, spatial computing UX / AR/VR/XR界面设计、空间计算UX |
| 💻 [macOS Spatial/Metal Engineer / macOS空间/Metal工程师](spatial-computing/macos-spatial-metal-engineer.md) | Swift, Metal, high-performance 3D / Swift、Metal、高性能3D | macOS spatial computing, Vision Pro native apps / macOS空间计算、Vision Pro原生应用 |
| 🌐 [XR Immersive Developer / XR沉浸式开发者](spatial-computing/xr-immersive-developer.md) | WebXR, browser-based AR/VR / WebXR、基于浏览器的AR/VR | Browser-based immersive experiences, WebXR apps / 基于浏览器的沉浸式体验、WebXR应用 |
| 🎮 [XR Cockpit Interaction Specialist / XR驾驶舱交互专家](spatial-computing/xr-cockpit-interaction-specialist.md) | Cockpit-based controls, immersive systems / 基于驾驶舱的控制、沉浸式系统 | Cockpit control systems, immersive control interfaces / 驾驶舱控制系统、沉浸式控制界面 |
| 🍎 [visionOS Spatial Engineer / visionOS空间工程师](spatial-computing/visionos-spatial-engineer.md) | Apple Vision Pro development / Apple Vision Pro开发 | Vision Pro apps, spatial computing experiences / Vision Pro应用、空间计算体验 |
| 🔌 [Terminal Integration Specialist / 终端集成专家](spatial-computing/terminal-integration-specialist.md) | Terminal integration, command-line tools / 终端集成、命令行工具 | CLI tools, terminal workflows, developer tools / CLI工具、终端工作流、开发者工具 |

### 🎯 Specialized Division / 专业部门

The unique specialists who don't fit in a box. / 不适合归类的独特专家。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎭 [Agents Orchestrator / 智能体编排器](specialized/agents-orchestrator.md) | Multi-agent coordination, workflow management / 多智能体协调、工作流管理 | Complex projects requiring multiple agent coordination / 需要多智能体协调的复杂项目 |
| 🔍 [LSP/Index Engineer / LSP/索引工程师](specialized/lsp-index-engineer.md) | Language Server Protocol, code intelligence / 语言服务器协议、代码智能 | Code intelligence systems, LSP implementation, semantic indexing / 代码智能系统、LSP实现、语义索引 |
| 📥 [Sales Data Extraction Agent / 销售数据提取智能体](specialized/sales-data-extraction-agent.md) | Excel monitoring, sales metric extraction / Excel监控、销售指标提取 | Sales data ingestion, MTD/YTD/Year End metrics / 销售数据摄取、MTD/YTD/年终指标 |
| 📈 [Data Consolidation Agent / 数据整合智能体](specialized/data-consolidation-agent.md) | Sales data aggregation, dashboard reports / 销售数据聚合、仪表板报告 | Territory summaries, rep performance, pipeline snapshots / 区域摘要、代表绩效、管道快照 |
| 📬 [Report Distribution Agent / 报告分发智能体](specialized/report-distribution-agent.md) | Automated report delivery / 自动报告交付 | Territory-based report distribution, scheduled sends / 基于区域的报告分发、定时发送 |
| 🔐 [Agentic Identity & Trust Architect / 智能体身份与信任架构师](specialized/agentic-identity-trust.md) | Agent identity, authentication, trust verification / 智能体身份、认证、信任验证 | Multi-agent identity systems, agent authorization, audit trails / 多智能体身份系统、智能体授权、审计追踪 |
| 🔗 [Identity Graph Operator / 身份图谱操作员](specialized/identity-graph-operator.md) | Shared identity resolution for multi-agent systems / 多智能体系统的共享身份解析 | Entity deduplication, merge proposals, cross-agent identity consistency / 实体去重、合并提案、跨智能体身份一致性 |
| 💸 [Accounts Payable Agent / 应付账款智能体](specialized/accounts-payable-agent.md) | Payment processing, vendor management, audit / 支付处理、供应商管理、审计 | Autonomous payment execution across crypto, fiat, stablecoins / 跨加密货币、法币、稳定币的自主支付执行 |
| 🛡️ [Blockchain Security Auditor / 区块链安全审计师](specialized/blockchain-security-auditor.md) | Smart contract audits, exploit analysis / 智能合约审计、漏洞分析 | Finding vulnerabilities in contracts before deployment / 在部署前发现合约漏洞 |
| 📋 [Compliance Auditor / 合规审计师](specialized/compliance-auditor.md) | SOC 2, ISO 27001, HIPAA, PCI-DSS | Guiding organizations through compliance certification / 指导组织完成合规认证 |
| 🌍 [Cultural Intelligence Strategist / 文化智能策略师](specialized/specialized-cultural-intelligence-strategist.md) | Global UX, representation, cultural exclusion / 全球UX、代表性、文化排斥 | Ensuring software resonates across cultures / 确保软件在不同文化中产生共鸣 |
| 🗣️ [Developer Advocate / 开发者倡导者](specialized/specialized-developer-advocate.md) | Community building, DX, developer content / 社区建设、开发者体验、开发者内容 | Bridging product and developer community / 连接产品与开发者社区 |
| 🔬 [Model QA Specialist / 模型QA专家](specialized/specialized-model-qa.md) | ML audits, feature analysis, interpretability / 机器学习审计、特征分析、可解释性 | End-to-end QA for machine learning models / 机器学习模型的端到端QA |
| 🗃️ [ZK Steward / ZK管理员](specialized/zk-steward.md) | Knowledge management, Zettelkasten, notes / 知识管理、Zettelkasten、笔记 | Building connected, validated knowledge bases / 构建互联的、经过验证的知识库 |
| 🔌 [MCP Builder / MCP构建者](specialized/specialized-mcp-builder.md) | Model Context Protocol servers, AI agent tooling / 模型上下文协议服务器、AI智能体工具 | Building MCP servers that extend AI agent capabilities / 构建扩展AI智能体能力的MCP服务器 |
| 📄 [Document Generator / 文档生成器](specialized/specialized-document-generator.md) | PDF, PPTX, DOCX, XLSX generation from code / 从代码生成PDF、PPTX、DOCX、XLSX | Professional document creation, reports, data visualization / 专业文档创建、报告、数据可视化 |
| ⚙️ [Automation Governance Architect / 自动化治理架构师](specialized/automation-governance-architect.md) | Automation governance, n8n, workflow auditing / 自动化治理、n8n、工作流审计 | Evaluating and governing business automations at scale / 大规模评估和管理业务自动化 |
| 📚 [Corporate Training Designer / 企业培训设计师](specialized/corporate-training-designer.md) | Enterprise training, curriculum development / 企业培训、课程开发 | Designing training systems and learning programs / 设计培训系统和学习计划 |
| 🏛️ [Government Digital Presales Consultant / 政府数字化售前顾问](specialized/government-digital-presales-consultant.md) | China ToG presales, digital transformation / 中国ToG售前、数字化转型 | Government digital transformation proposals and bids / 政府数字化转型提案和投标 |
| ⚕️ [Healthcare Marketing Compliance / 医疗营销合规](specialized/healthcare-marketing-compliance.md) | China healthcare advertising compliance / 中国医疗广告合规 | Healthcare marketing regulatory compliance / 医疗营销监管合规 |
| 🎯 [Recruitment Specialist / 招聘专家](specialized/recruitment-specialist.md) | Talent acquisition, recruiting operations / 人才获取、招聘运营 | Recruitment strategy, sourcing, and hiring processes / 招聘策略、人才搜寻和招聘流程 |
| 🎓 [Study Abroad Advisor / 留学顾问](specialized/study-abroad-advisor.md) | International education, application planning / 国际教育、申请规划 | Study abroad planning across US, UK, Canada, Australia / 美国、英国、加拿大、澳大利亚留学规划 |
| 🔗 [Supply Chain Strategist / 供应链策略师](specialized/supply-chain-strategist.md) | Supply chain management, procurement strategy / 供应链管理、采购策略 | Supply chain optimization and procurement planning / 供应链优化和采购规划 |
| 🗺️ [Workflow Architect / 工作流架构师](specialized/specialized-workflow-architect.md) | Workflow discovery, mapping, and specification / 工作流发现、映射和规范 | Mapping every path through a system before code is written / 在编写代码之前映射系统的每条路径 |
| ☁️ [Salesforce Architect / Salesforce架构师](specialized/specialized-salesforce-architect.md) | Multi-cloud Salesforce design, governor limits, integrations / 多云Salesforce设计、治理限制、集成 | Enterprise Salesforce architecture, org strategy, deployment pipelines / 企业Salesforce架构、组织策略、部署管道 |
| 🇫🇷 [French Consulting Market Navigator / 法国咨询市场导航员](specialized/specialized-french-consulting-market.md) | ESN/SI ecosystem, portage salarial, rate positioning / ESN/SI生态系统、portage salarial、费率定位 | Freelance consulting in the French IT market / 在法国IT市场从事自由咨询 |
| 🇰🇷 [Korean Business Navigator / 韩国商务导航员](specialized/specialized-korean-business-navigator.md) | Korean business culture, 품의 process, relationship mechanics / 韩国商业文化、품의流程、关系机制 | Foreign professionals navigating Korean business relationships / 外国专业人士 navigating 韩国商务关系 |
| 🏗️ [Civil Engineer / 土木工程师](specialized/specialized-civil-engineer.md) | Structural analysis, geotechnical design, global building codes / 结构分析、岩土设计、全球建筑规范 | Multi-standard structural engineering across Eurocode, ACI, AISC, and more / 跨Eurocode、ACI、AISC等的多标准结构工程 |
| 🎧 [Customer Service / 客户服务](specialized/customer-service.md) | Omnichannel support, complaint handling, retention, escalation / 全渠道支持、投诉处理、留存、升级 | Any industry customer support — retail, SaaS, hospitality, finance, logistics / 任何行业客户支持 — 零售、SaaS、酒店、金融、物流 |
| 🏥 [Healthcare Customer Service / 医疗客户服务](specialized/healthcare-customer-service.md) | HIPAA-aware patient support, billing, insurance, emergency routing / HIPAA感知患者支持、账单、保险、紧急路由 | Healthcare organizations needing compliant, empathetic patient support / 需要合规、富有同理心的患者支持的医疗机构 |
| 🏨 [Hospitality Guest Services / 酒店宾客服务](specialized/hospitality-guest-services.md) | Reservations, concierge, complaint recovery, loyalty, events / 预订、礼宾、投诉恢复、忠诚度、活动 | Hotels, resorts, restaurants, and event venues / 酒店、度假村、餐厅和活动场地 |
| 🤝 [HR Onboarding / HR入职](specialized/hr-onboarding.md) | Pre-boarding, compliance, benefits enrollment, 30-60-90 day plans / 入职前、合规、福利登记、30-60-90天计划 | Any company onboarding new hires — from startups to enterprise / 任何公司新员工入职 — 从初创企业到大型企业 |
| 🌐 [Language Translator / 语言翻译](specialized/language-translator.md) | Spanish ↔ English translation, dialect awareness, cultural context / 西班牙语 ↔ 英语翻译、方言意识、文化背景 | Travel, business, medical, and legal translation needs / 旅行、商务、医疗和法律翻译需求 |
| ⏱️ [Legal Billing & Time Tracking / 法律计费和工时追踪](specialized/legal-billing-time-tracking.md) | Time capture, billing narratives, IOLTA compliance, collections / 时间记录、计费叙述、IOLTA合规、收款 | Law firms maximizing revenue recovery and billing accuracy / 律师事务所最大化收入回收和计费准确性 |
| 📋 [Legal Client Intake / 法律客户接待](specialized/legal-client-intake.md) | Prospect qualification, conflict screening, consultation scheduling / 潜在客户资格评估、利益冲突筛查、咨询预约 | Law firms converting inquiries into retained clients / 律师事务所将咨询转化为委托客户 |
| ⚖️ [Legal Document Review / 法律文件审查](specialized/legal-document-review.md) | Contract review, risk flagging, version comparison, compliance / 合同审查、风险标记、版本比较、合规 | Attorney-ready first-pass review across any practice area / 任何执业领域的律师就绪初审 |
| 🏦 [Loan Officer Assistant / 贷款专员助理](specialized/loan-officer-assistant.md) | Borrower intake, TRID compliance, pipeline tracking, closing coordination / 借款人接待、TRID合规、管道追踪、交割协调 | Mortgage and consumer lending teams / 抵押贷款和消费贷款团队 |
| 🏠 [Real Estate Buyer & Seller / 房地产买卖双方](specialized/real-estate-buyer-seller.md) | Buyer/seller representation, offers, transaction coordination / 买方/卖方代表、报价、交易协调 | Residential and investment real estate transactions / 住宅和投资房地产交易 |
| 🛒 [Retail Customer Returns / 零售客户退货](specialized/retail-customer-returns.md) | Return processing, fraud prevention, exchanges, vendor returns / 退货处理、欺诈预防、换货、供应商退货 | Brick-and-mortar, e-commerce, and omnichannel retail / 实体店、电商和全渠道零售 |

### 💵 Finance Division / 财务部门

Accounting, financial analysis, tax strategy, and investment research specialists. / 会计、财务分析、税务策略和投资研究专家。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 📒 [Bookkeeper & Controller / 记账员与财务主管](finance/finance-bookkeeper-controller.md) | Month-end close, reconciliation, GAAP compliance, internal controls / 月末结账、对账、GAAP合规、内部控制 | Day-to-day accounting operations, audit readiness, financial record-keeping / 日常会计运营、审计准备、财务记录保存 |
| 📊 [Financial Analyst / 财务分析师](finance/finance-financial-analyst.md) | Financial modeling, forecasting, scenario analysis, decision support / 财务建模、预测、情景分析、决策支持 | Three-statement models, variance analysis, data-driven business intelligence / 三表模型、差异分析、数据驱动商业智能 |
| 📈 [FP&A Analyst / 财务规划与分析分析师](finance/finance-fpa-analyst.md) | Budgeting, rolling forecasts, variance analysis, business reviews / 预算、滚动预测、差异分析、业务审查 | Annual operating plans, monthly business reviews, strategic resource allocation / 年度运营计划、月度业务审查、战略资源分配 |
| 🔍 [Investment Researcher / 投资研究员](finance/finance-investment-researcher.md) | Due diligence, portfolio analysis, asset valuation, equity research / 尽职调查、组合分析、资产估值、股票研究 | Investment thesis development, risk assessment, market research / 投资论点开发、风险评估、市场研究 |
| 🏛️ [Tax Strategist / 税务策略师](finance/finance-tax-strategist.md) | Tax optimization, multi-jurisdictional compliance, transfer pricing / 税务优化、多司法管辖区合规、转让定价 | Entity structuring, ETR analysis, audit defense, strategic tax planning / 实体结构、ETR分析、审计辩护、战略性税务规划 |

### 🎮 Game Development Division / 游戏开发部门

Building worlds, systems, and experiences across every major engine. / 在每个主要引擎上构建世界、系统和体验。

#### Cross-Engine Agents (Engine-Agnostic) / 跨引擎智能体（与引擎无关）

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🎯 [Game Designer / 游戏设计师](game-development/game-designer.md) | Systems design, GDD authorship, economy balancing, gameplay loops / 系统设计、GDD编写、经济平衡、游戏循环 | Designing game mechanics, progression systems, writing design documents / 设计游戏机制、进度系统、编写设计文档 |
| 🗺️ [Level Designer / 关卡设计师](game-development/level-designer.md) | Layout theory, pacing, encounter design, environmental storytelling / 布局理论、节奏、遭遇设计、环境叙事 | Building levels, designing encounter flow, spatial narrative / 构建关卡、设计遭遇流程、空间叙事 |
| 🎨 [Technical Artist / 技术美术](game-development/technical-artist.md) | Shaders, VFX, LOD pipeline, art-to-engine optimization / 着色器、VFX、LOD管道、美术到引擎优化 | Bridging art and engineering, shader authoring, performance-safe asset pipelines / 连接美术和工程、着色器编写、性能安全的资源管道 |
| 🔊 [Game Audio Engineer / 游戏音频工程师](game-development/game-audio-engineer.md) | FMOD/Wwise, adaptive music, spatial audio, audio budgets / FMOD/Wwise、自适应音乐、空间音频、音频预算 | Interactive audio systems, dynamic music, audio performance / 交互式音频系统、动态音乐、音频性能 |
| 📖 [Narrative Designer / 叙事设计师](game-development/narrative-designer.md) | Story systems, branching dialogue, lore architecture / 故事系统、分支对话、背景架构 | Writing branching narratives, implementing dialogue systems, world lore / 编写分支叙事、实现对话系统、世界背景 |

#### Unity / Unity引擎

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🏗️ [Unity Architect / Unity架构师](game-development/unity/unity-architect.md) | ScriptableObjects, data-driven modularity, DOTS/ECS / ScriptableObjects、数据驱动模块化、DOTS/ECS | Large-scale Unity projects, data-driven system design, ECS performance work / 大规模Unity项目、数据驱动系统设计、ECS性能工作 |
| ✨ [Unity Shader Graph Artist / Unity Shader Graph美术](game-development/unity/unity-shader-graph-artist.md) | Shader Graph, HLSL, URP/HDRP, Renderer Features / Shader Graph、HLSL、URP/HDRP、渲染器功能 | Custom Unity materials, VFX shaders, post-processing passes / 自定义Unity材质、VFX着色器、后处理通道 |
| 🌐 [Unity Multiplayer Engineer / Unity多人游戏工程师](game-development/unity/unity-multiplayer-engineer.md) | Netcode for GameObjects, Unity Relay/Lobby, server authority, prediction / Netcode for GameObjects、Unity Relay/Lobby、服务器权威、预测 | Online Unity games, client prediction, Unity Gaming Services integration / 在线Unity游戏、客户端预测、Unity游戏服务集成 |
| 🛠️ [Unity Editor Tool Developer / Unity编辑器工具开发者](game-development/unity/unity-editor-tool-developer.md) | EditorWindows, AssetPostprocessors, PropertyDrawers, build validation / EditorWindows、AssetPostprocessors、PropertyDrawers、构建验证 | Custom Unity Editor tooling, pipeline automation, content validation / 自定义Unity编辑器工具、管道自动化、内容验证 |

#### Unreal Engine / 虚幻引擎

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| ⚙️ [Unreal Systems Engineer / 虚幻系统工程师](game-development/unreal-engine/unreal-systems-engineer.md) | C++/Blueprint hybrid, GAS, Nanite constraints, memory management / C++/蓝图混合、GAS、Nanite限制、内存管理 | Complex Unreal gameplay systems, Gameplay Ability System, engine-level C++ / 复杂虚幻游戏系统、游戏能力系统、引擎级C++ |
| 🎨 [Unreal Technical Artist / 虚幻技术美术](game-development/unreal-engine/unreal-technical-artist.md) | Material Editor, Niagara, PCG, Substrate / 材质编辑器、Niagara、PCG、Substrate | Unreal materials, Niagara VFX, procedural content generation / 虚幻材质、Niagara VFX、程序化内容生成 |
| 🌐 [Unreal Multiplayer Architect / 虚幻多人游戏架构师](game-development/unreal-engine/unreal-multiplayer-architect.md) | Actor replication, GameMode/GameState hierarchy, dedicated server / Actor复制、GameMode/GameState层级、专用服务器 | Unreal online games, replication graphs, server authoritative Unreal / 虚幻在线游戏、复制图、服务器权威虚幻 |
| 🗺️ [Unreal World Builder / 虚幻世界构建者](game-development/unreal-engine/unreal-world-builder.md) | World Partition, Landscape, HLOD, LWC / 世界分区、地形、HLOD、LWC | Large open-world Unreal levels, streaming systems, terrain at scale / 大型开放世界虚幻关卡、流送系统、大规模地形 |

#### Godot / Godot引擎

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 📜 [Godot Gameplay Scripter / Godot游戏玩法脚本师](game-development/godot/godot-gameplay-scripter.md) | GDScript 2.0, signals, composition, static typing / GDScript 2.0、信号、组合、静态类型 | Godot gameplay systems, scene composition, performance-conscious GDScript / Godot游戏系统、场景组合、性能意识GDScript |
| 🌐 [Godot Multiplayer Engineer / Godot多人游戏工程师](game-development/godot/godot-multiplayer-engineer.md) | MultiplayerAPI, ENet/WebRTC, RPCs, authority model / MultiplayerAPI、ENet/WebRTC、RPC、权威模型 | Online Godot games, scene replication, server-authoritative Godot / 在线Godot游戏、场景复制、服务器权威Godot |
| ✨ [Godot Shader Developer / Godot着色器开发者](game-development/godot/godot-shader-developer.md) | Godot shading language, VisualShader, RenderingDevice / Godot着色语言、VisualShader、RenderingDevice | Custom Godot materials, 2D/3D effects, post-processing, compute shaders / 自定义Godot材质、2D/3D效果、后处理、计算着色器 |

#### Blender / Blender

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🧩 [Blender Addon Engineer / Blender插件工程师](game-development/blender/blender-addon-engineer.md) | Blender Python (`bpy`), custom operators/panels, asset validators, exporters, pipeline automation / Blender Python (`bpy`)、自定义操作符/面板、资源验证器、导出器、管道自动化 | Building Blender add-ons, asset prep tools, export workflows, and DCC pipeline automation / 构建Blender插件、资源准备工具、导出工作流和DCC管道自动化 |

#### Roblox Studio / Roblox工作室

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| ⚙️ [Roblox Systems Scripter / Roblox系统脚本师](game-development/roblox-studio/roblox-systems-scripter.md) | Luau, RemoteEvents/Functions, DataStore, server-authoritative module architecture / Luau、RemoteEvents/Functions、DataStore、服务器权威模块架构 | Building secure Roblox game systems, client-server communication, data persistence / 构建安全的Roblox游戏系统、客户端-服务器通信、数据持久化 |
| 🎯 [Roblox Experience Designer / Roblox体验设计师](game-development/roblox-studio/roblox-experience-designer.md) | Engagement loops, monetization, D1/D7 retention, onboarding flow / 参与循环、货币化、D1/D7留存、新手引导流程 | Designing Roblox game loops, Game Passes, daily rewards, player retention / 设计Roblox游戏循环、游戏通行证、每日奖励、玩家留存 |
| 👗 [Roblox Avatar Creator / Roblox虚拟形象创作者](game-development/roblox-studio/roblox-avatar-creator.md) | UGC pipeline, accessory rigging, Creator Marketplace submission / UGC管道、配件绑定、创作者市场提交 | Roblox UGC items, HumanoidDescription customization, in-experience avatar shops / Roblox UGC物品、HumanoidDescription定制、体验内虚拟形象商店 |

### 📚 Academic Division / 学术部门

Scholarly rigor for world-building, storytelling, and narrative design. / 用于世界构建、叙事和叙事设计的学术严谨性。

| Agent / 智能体 | Specialty / 专长 | When to Use / 何时使用 |
|-------|-----------|-------------|
| 🌍 [Anthropologist / 人类学家](academic/academic-anthropologist.md) | Cultural systems, kinship, rituals, belief systems / 文化系统、亲属关系、仪式、信仰体系 | Designing culturally coherent societies with internal logic / 设计具有内在逻辑的文化连贯社会 |
| 🌐 [Geographer / 地理学家](academic/academic-geographer.md) | Physical/human geography, climate, cartography / 自然/人文地理、气候、制图 | Building geographically coherent worlds with realistic terrain and settlements / 构建具有真实地形和聚落的地理连贯世界 |
| 📚 [Historian / 历史学家](academic/academic-historian.md) | Historical analysis, periodization, material culture / 历史分析、分期、物质文化 | Validating historical coherence, enriching settings with authentic period detail / 验证历史连贯性、用真实的时代细节丰富背景 |
| 📜 [Narratologist / 叙事学家](academic/academic-narratologist.md) | Narrative theory, story structure, character arcs / 叙事理论、故事结构、角色弧线 | Analyzing and improving story structure with established theoretical frameworks / 用成熟的理论框架分析和改进故事结构 |
| 🧠 [Psychologist / 心理学家](academic/academic-psychologist.md) | Personality theory, motivation, cognitive patterns / 人格理论、动机、认知模式 | Building psychologically credible characters grounded in research / 基于研究构建心理上可信的角色 |

---

## 🎯 Real-World Use Cases / 实际使用案例

### Scenario 1: Building a Startup MVP / 场景1：构建初创公司MVP

**Your Team / 您的团队**:
1. 🎨 **Frontend Developer / 前端开发者** - Build the React app / 构建React应用
2. 🏗️ **Backend Architect / 后端架构师** - Design the API and database / 设计API和数据库
3. 🚀 **Growth Hacker / 增长黑客** - Plan user acquisition / 规划用户获取
4. ⚡ **Rapid Prototyper / 快速原型师** - Fast iteration cycles / 快速迭代周期
5. 🔍 **Reality Checker / 现实检验者** - Ensure quality before launch / 确保发布前的质量

**Result / 结果**: Ship faster with specialized expertise at every stage. / 在每个阶段都有专业专业知识，更快发布。

---

### Scenario 2: Marketing Campaign Launch / 场景2：营销活动发布

**Your Team / 您的团队**:
1. 📝 **Content Creator / 内容创作者** - Develop campaign content / 开发活动内容
2. 🐦 **Twitter Engager / Twitter互动专家** - Twitter strategy and execution / Twitter策略和执行
3. 📸 **Instagram Curator / Instagram策展人** - Visual content and stories / 视觉内容和故事
4. 🤝 **Reddit Community Builder / Reddit社区建设者** - Authentic community engagement / 真实的社区互动
5. 📊 **Analytics Reporter / 分析报告员** - Track and optimize performance / 追踪和优化性能

**Result / 结果**: Multi-channel coordinated campaign with platform-specific expertise. / 具有平台特定专业知识的多渠道协调活动。

---

### Scenario 3: Enterprise Feature Development / 场景3：企业功能开发

**Your Team / 您的团队**:
1. 👔 **Senior Project Manager / 高级项目经理** - Scope and task planning / 范围和任务规划
2. 💎 **Senior Developer / 高级开发者** - Complex implementation / 复杂实现
3. 🎨 **UI Designer / UI设计师** - Design system and components / 设计系统和组件
4. 🧪 **Experiment Tracker / 实验追踪器** - A/B test planning / A/B测试规划
5. 📸 **Evidence Collector / 证据收集者** - Quality verification / 质量验证
6. 🔍 **Reality Checker / 现实检验者** - Production readiness / 生产就绪

**Result / 结果**: Enterprise-grade delivery with quality gates and documentation. / 具有质量门禁和文档的企业级交付。

---

### Scenario 4: Paid Media Account Takeover / 场景4：付费媒体账户接管

**Your Team / 您的团队**:

1. 📋 **Paid Media Auditor / 付费媒体审计师** - Comprehensive account assessment / 全面账户评估
2. 📡 **Tracking & Measurement Specialist / 追踪与测量专家** - Verify conversion tracking accuracy / 验证转化追踪准确性
3. 💰 **PPC Campaign Strategist / PPC活动策略师** - Redesign account architecture / 重新设计账户架构
4. 🔍 **Search Query Analyst / 搜索查询分析师** - Clean up wasted spend from search terms / 清理搜索词的浪费支出
5. ✍️ **Ad Creative Strategist / 广告创意策略师** - Refresh all ad copy and extensions / 刷新所有广告文案和扩展
6. 📊 **Analytics Reporter / 分析报告员** (Support Division / 支持部门) - Build reporting dashboards / 构建报告仪表板

**Result / 结果**: Systematic account takeover with tracking verified, waste eliminated, structure optimized, and creative refreshed — all within the first 30 days. / 在前30天内完成系统性的账户接管，包括验证追踪、消除浪费、优化结构和刷新创意。

---

### Scenario 5: Full Agency Product Discovery / 场景5：全机构产品发现

**Your Team / 您的团队**: All 8 divisions working in parallel on a single mission. / 所有8个部门并行协作完成一个使命。

See the **[Nexus Spatial Discovery Exercise](examples/nexus-spatial-discovery.md)** -- a complete example where 8 agents (Product Trend Researcher, Backend Architect, Brand Guardian, Growth Hacker, Support Responder, UX Researcher, Project Shepherd, and XR Interface Architect) were deployed simultaneously to evaluate a software opportunity and produce a unified product plan covering market validation, technical architecture, brand strategy, go-to-market, support systems, UX research, project execution, and spatial UI design.

请参阅 **[Nexus空间发现练习](examples/nexus-spatial-discovery.md)** —— 一个完整的示例，其中8个智能体（产品趋势研究员、后端架构师、品牌守护者、增长黑客、支持响应者、UX研究员、项目牧羊人和XR界面架构师）被同时部署，以评估一个软件机会并生成一个统一的产品计划，涵盖市场验证、技术架构、品牌战略、市场进入、支持系统、UX研究、项目执行和空间UI设计。

**Result / 结果**: Comprehensive, cross-functional product blueprint produced in a single session. [More examples](examples/). / 在一个会话中生成全面的跨职能产品蓝图。[更多示例](examples/)。

---

## 🤝 Contributing / 贡献

We welcome contributions! Here's how you can help: / 我们欢迎贡献！以下是您可以提供帮助的方式：

### Add a New Agent / 添加新智能体

1. Fork the repository / Fork仓库
2. Create a new agent file in the appropriate category / 在适当的类别中创建新的智能体文件
3. Follow the agent template structure: / 遵循智能体模板结构：
   - Frontmatter with name, description, color / 带有名称、描述、颜色的前言
   - Identity & Memory section / 身份与记忆部分
   - Core Mission / 核心使命
   - Critical Rules (domain-specific) / 关键规则（领域特定）
   - Technical Deliverables with examples / 带有示例的技术交付成果
   - Workflow Process / 工作流程
   - Success Metrics / 成功指标
4. Submit a PR with your agent / 提交包含您智能体的PR

### Improve Existing Agents / 改进现有智能体

- Add real-world examples / 添加真实示例
- Enhance code samples / 增强代码示例
- Update success metrics / 更新成功指标
- Improve workflows / 改进工作流程

### Share Your Success Stories / 分享您的成功故事

Have you used these agents successfully? Share your story in the [Discussions](https://github.com/msitarzewski/agency-agents/discussions)! / 您成功使用过这些智能体吗？在[讨论区](https://github.com/msitarzewski/agency-agents/discussions)分享您的故事！

---

## 📖 Agent Design Philosophy / 智能体设计理念

Each agent is designed with: / 每个智能体的设计都包含：

1. **🎭 Strong Personality / 强烈的个性**: Not generic templates - real character and voice / 不是通用模板 — 真实的性格和声音
2. **📋 Clear Deliverables / 清晰的交付成果**: Concrete outputs, not vague guidance / 具体的输出，而非模糊的指南
3. **✅ Success Metrics / 成功指标**: Measurable outcomes and quality standards / 可衡量的成果和质量标准
4. **🔄 Proven Workflows / 成熟的工作流程**: Step-by-step processes that work / 行之有效的分步流程
5. **💡 Learning Memory / 学习记忆**: Pattern recognition and continuous improvement / 模式识别和持续改进

---

## 🎁 What Makes This Special? / 是什么让这特别？

### Unlike Generic AI Prompts: / 与通用AI提示不同：
- ❌ Generic "Act as a developer" prompts / 通用的"扮演开发者"提示
- ✅ Deep specialization with personality and process / 具有个性和流程的深度专业化

### Unlike Prompt Libraries: / 与提示库不同：
- ❌ One-off prompt collections / 一次性的提示集合
- ✅ Comprehensive agent systems with workflows and deliverables / 具有工作流程和交付成果的综合智能体系统

### Unlike AI Tools: / 与AI工具不同：
- ❌ Black box tools you can't customize / 无法定制的黑盒工具
- ✅ Transparent, forkable, adaptable agent personalities / 透明、可fork、可适应的智能体个性

---

## 🎨 Agent Personality Highlights / 智能体个性亮点

> "I don't just test your code - I default to finding 3-5 issues and require visual proof for everything."
> "我不仅仅测试您的代码 — 我默认会找到3-5个问题，并要求所有内容的视觉证明。"
>
> -- **Evidence Collector / 证据收集者** (Testing Division / 测试部门)

> "You're not marketing on Reddit - you're becoming a valued community member who happens to represent a brand."
> "您不是在Reddit上做营销 — 您正在成为一位恰好代表品牌的受重视社区成员。"
>
> -- **Reddit Community Builder / Reddit社区建设者** (Marketing Division / 市场部门)

> "Every playful element must serve a functional or emotional purpose. Design delight that enhances rather than distracts."
> "每个有趣的元素都必须服务于功能或情感目的。设计愉悦感以增强而非分散注意力。"
>
> -- **Whimsy Injector / 趣味注入者** (Design Division / 设计部门)

> "Let me add a celebration animation that reduces task completion anxiety by 40%"
> "让我添加一个庆祝动画，将任务完成焦虑降低40%"
>
> -- **Whimsy Injector / 趣味注入者** (during a UX review / 在UX审查期间)

---

## 📊 Stats / 统计数据

- 🎭 **144 Specialized Agents / 144个专业智能体** across 12 divisions / 跨越12个部门
- 📝 **10,000+ lines / 10,000+行** of personality, process, and code examples / 个性、流程和代码示例
- ⏱️ **Months of iteration / 数月的迭代** from real-world usage / 来自实际使用
- 🌟 **Battle-tested / 经过实战检验** in production environments / 在生产环境中
- 💬 **50+ requests / 50+请求** in first 12 hours on Reddit / 在Reddit上发布后的前12小时内

---

## 🔌 Multi-Tool Integrations / 多工具集成

The Agency works natively with Claude Code, and ships conversion + install scripts so you can use the same agents across every major agentic coding tool.

The Agency原生支持Claude Code，并提供转换+安装脚本，因此您可以在每个主要的智能编码工具中使用相同的智能体。

### Supported Tools / 支持的工具

- **[Claude Code](https://claude.ai/code)** — native `.md` agents, no conversion needed → `~/.claude/agents/` / 原生`.md`智能体，无需转换
- **[GitHub Copilot](https://github.com/copilot)** — native `.md` agents, no conversion needed → `~/.github/agents/` + `~/.copilot/agents/` / 原生`.md`智能体，无需转换
- **[Antigravity](https://github.com/google-gemini/antigravity)** — `SKILL.md` per agent → `~/.gemini/antigravity/skills/` / 每个智能体一个`SKILL.md`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — extension + `SKILL.md` files → `~/.gemini/extensions/agency-agents/` / 扩展 + `SKILL.md`文件
- **[OpenCode](https://opencode.ai)** — `.md` agent files → `.opencode/agents/` / `.md`智能体文件
- **[Cursor](https://cursor.sh)** — `.mdc` rule files → `.cursor/rules/` / `.mdc`规则文件
- **[Aider](https://aider.chat)** — single `CONVENTIONS.md` → `./CONVENTIONS.md` / 单个`CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** — single `.windsurfrules` → `./.windsurfrules` / 单个`.windsurfrules`
- **[OpenClaw](https://github.com/openclaw/openclaw)** — `SOUL.md` + `AGENTS.md` + `IDENTITY.md` per agent / 每个智能体`SOUL.md` + `AGENTS.md` + `IDENTITY.md`
- **[Qwen Code](https://github.com/QwenLM/qwen-code)** — `.md` SubAgent files → `~/.qwen/agents/` / `.md` SubAgent文件
- **[Kimi Code](https://github.com/MoonshotAI/kimi-cli)** — YAML agent specs → `~/.config/kimi/agents/` / YAML智能体规格

---

### ⚡ Quick Install / 快速安装

**Step 1 -- Generate integration files: / 第1步 -- 生成集成文件：**
```bash
./scripts/convert.sh
# Faster (parallel, output order may vary): ./scripts/convert.sh --parallel
# 更快（并行，输出顺序可能不同）：./scripts/convert.sh --parallel
```

**Step 2 -- Install (interactive, auto-detects your tools): / 第2步 -- 安装（交互式，自动检测您的工具）：**
```bash
./scripts/install.sh
# Faster (parallel, output order may vary): ./scripts/install.sh --no-interactive --parallel
# 更快（并行，输出顺序可能不同）：./scripts/install.sh --no-interactive --parallel
```

The installer scans your system for installed tools, shows a checkbox UI, and lets you pick exactly what to install:
安装程序会扫描您的系统以查找已安装的工具，显示复选框UI，并让您精确选择要安装的内容：

```
  +------------------------------------------------+
  |   The Agency -- Tool Installer                 |
  |   The Agency -- 工具安装程序                   |
  +------------------------------------------------+

  System scan: [*] = detected on this machine / 系统扫描：[*] = 在此机器上检测到

  [x]  1)  [*]  Claude Code     (claude.ai/code)
  [x]  2)  [*]  Copilot         (~/.github + ~/.copilot)
  [x]  3)  [*]  Antigravity     (~/.gemini/antigravity)
  [ ]  4)  [ ]  Gemini CLI      (gemini extension)
  [ ]  5)  [ ]  OpenCode        (opencode.ai)
  [ ]  6)  [ ]  OpenClaw        (~/.openclaw/agency-agents)
  [x]  7)  [*]  Cursor          (.cursor/rules)
  [ ]  8)  [ ]  Aider           (CONVENTIONS.md)
  [ ]  9)  [ ]  Windsurf        (.windsurfrules)
  [ ] 10)  [ ]  Qwen Code       (~/.qwen/agents)
  [ ] 11)  [ ]  Kimi Code       (~/.config/kimi/agents)

  [1-11] toggle   [a] all   [n] none   [d] detected
  [Enter] install   [q] quit
```

**Or install a specific tool directly: / 或直接安装特定工具：**
```bash
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool antigravity
```

**Non-interactive (CI/scripts): / 非交互式（CI/脚本）：**
```bash
./scripts/install.sh --no-interactive --tool all
```

**Faster runs (parallel) / 更快的运行（并行）** — On multi-core machines, use `--parallel` so each tool is processed in parallel. Output order across tools is non-deterministic. Works with both interactive and non-interactive install: e.g. `./scripts/install.sh --interactive --parallel` (pick tools, then install in parallel) or `./scripts/install.sh --no-interactive --parallel`. Job count defaults to `nproc` (Linux), `sysctl -n hw.ncpu` (macOS), or 4; override with `--jobs N`.

在多核机器上，使用`--parallel`以便并行处理每个工具。跨工具的输出顺序是非确定性的。适用于交互式和非交互式安装：例如`./scripts/install.sh --interactive --parallel`（选择工具，然后并行安装）或`./scripts/install.sh --no-interactive --parallel`。作业数默认为`nproc`（Linux）、`sysctl -n hw.ncpu`（macOS）或4；使用`--jobs N`覆盖。

```bash
./scripts/convert.sh --parallel                    # convert all tools in parallel / 并行转换所有工具
./scripts/convert.sh --parallel --jobs 8           # cap parallel jobs / 限制并行作业数
./scripts/install.sh --no-interactive --parallel   # install all detected tools in parallel / 并行安装所有检测到的工具
./scripts/install.sh --interactive --parallel      # pick tools, then install in parallel / 选择工具，然后并行安装
./scripts/install.sh --no-interactive --parallel --jobs 4
```

---

### Tool-Specific Instructions / 工具特定说明

<details>
<summary><strong>Claude Code</strong></summary>

Agents are copied directly from the repo into `~/.claude/agents/` -- no conversion needed.
智能体直接从仓库复制到`~/.claude/agents/` — 无需转换。

```bash
./scripts/install.sh --tool claude-code
```

Then activate in Claude Code: / 然后在Claude Code中激活：
```
Use the Frontend Developer agent to review this component.
使用前端开发者智能体审查此组件。
```

See [integrations/claude-code/README.md](integrations/claude-code/README.md) for details.
</details>

<details>
<summary><strong>GitHub Copilot</strong></summary>

Agents are copied directly from the repo into `~/.github/agents/` and `~/.copilot/agents/` -- no conversion needed.
智能体直接从仓库复制到`~/.github/agents/`和`~/.copilot/agents/` — 无需转换。

```bash
./scripts/install.sh --tool copilot
```

Then activate in GitHub Copilot: / 然后在GitHub Copilot中激活：
```
Use the Frontend Developer agent to review this component.
使用前端开发者智能体审查此组件。
```

See [integrations/github-copilot/README.md](integrations/github-copilot/README.md) for details.
</details>

<details>
<summary><strong>Antigravity (Gemini)</strong></summary>

Each agent becomes a skill in `~/.gemini/antigravity/skills/agency-<slug>/`.
每个智能体成为`~/.gemini/antigravity/skills/agency-<slug>/`中的一个技能。

```bash
./scripts/install.sh --tool antigravity
```

Activate in Gemini with Antigravity: / 在Gemini中使用Antigravity激活：
```
@agency-frontend-developer review this React component
@agency-frontend-developer 审查此React组件
```

See [integrations/antigravity/README.md](integrations/antigravity/README.md) for details.
</details>

<details>
<summary><strong>Gemini CLI</strong></summary>

Installs as a Gemini CLI extension with one skill per agent plus a manifest.
On a fresh clone, generate the Gemini extension files before running the installer.
作为Gemini CLI扩展安装，每个智能体一个技能加一个清单。
在全新克隆时，在运行安装程序之前生成Gemini扩展文件。

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

See [integrations/gemini-cli/README.md](integrations/gemini-cli/README.md) for details.
</details>

<details>
<summary><strong>OpenCode</strong></summary>

Agents are placed in `.opencode/agents/` in your project root (project-scoped).
智能体放置在项目根目录的`.opencode/agents/`中（项目范围）。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

Or install globally: / 或全局安装：
```bash
mkdir -p ~/.config/opencode/agents
cp integrations/opencode/agents/*.md ~/.config/opencode/agents/
```

Activate in OpenCode: / 在OpenCode中激活：
```
@backend-architect design this API.
@backend-architect 设计此API。
```

See [integrations/opencode/README.md](integrations/opencode/README.md) for details.
</details>

<details>
<summary><strong>Cursor</strong></summary>

Each agent becomes a `.mdc` rule file in `.cursor/rules/` of your project.
每个智能体成为您项目`.cursor/rules/`中的`.mdc`规则文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

Rules are auto-applied when Cursor detects them in the project. Reference them explicitly:
当Cursor在项目中检测到规则时，会自动应用。显式引用它们：
```
Use the @security-engineer rules to review this code.
使用@security-engineer规则审查此代码。
```

See [integrations/cursor/README.md](integrations/cursor/README.md) for details.
</details>

<details>
<summary><strong>Aider</strong></summary>

All agents are compiled into a single `CONVENTIONS.md` file that Aider reads automatically.
所有智能体编译成Aider自动读取的单个`CONVENTIONS.md`文件。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

Then reference agents in your Aider session: / 然后在Aider会话中引用智能体：
```
Use the Frontend Developer agent to refactor this component.
使用前端开发者智能体重构此组件。
```

See [integrations/aider/README.md](integrations/aider/README.md) for details.
</details>

<details>
<summary><strong>Windsurf</strong></summary>

All agents are compiled into `.windsurfrules` in your project root.
所有智能体编译到您项目根目录的`.windsurfrules`中。

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool windsurf
```

Reference agents in Windsurf's Cascade: / 在Windsurf的Cascade中引用智能体：
```
Use the Reality Checker agent to verify this is production ready.
使用现实检验者智能体验证此内容是否已准备好生产。
```

See [integrations/windsurf/README.md](integrations/windsurf/README.md) for details.
</details>

<details>
<summary><strong>OpenClaw</strong></summary>

Each agent becomes a workspace with `SOUL.md`, `AGENTS.md`, and `IDENTITY.md` in `~/.openclaw/agency-agents/`.
每个智能体成为`~/.openclaw/agency-agents/`中具有`SOUL.md`、`AGENTS.md`和`IDENTITY.md`的工作空间。

```bash
./scripts/convert.sh --tool openclaw
./scripts/install.sh --tool openclaw
```

If the `openclaw` CLI is available, the installer registers each workspace automatically.
Run `openclaw gateway restart` after installation so the new agents are activated.
如果`openclaw` CLI可用，安装程序会自动注册每个工作空间。
安装后运行`openclaw gateway restart`以激活新智能体。

See [integrations/openclaw/README.md](integrations/openclaw/README.md) for details.

</details>

<details>
<summary><strong>Qwen Code</strong></summary>

SubAgents are installed to `.qwen/agents/` in your project root (project-scoped).
SubAgents安装到项目根目录的`.qwen/agents/`中（项目范围）。

```bash
# Convert and install (run from your project root) / 转换和安装（从项目根目录运行）
cd /your/project
./scripts/convert.sh --tool qwen
./scripts/install.sh --tool qwen
```

**Usage in Qwen Code: / 在Qwen Code中使用：**
- Reference by name: `Use the frontend-developer agent to review this component` / 按名称引用：`使用frontend-developer智能体审查此组件`
- Or let Qwen auto-delegate based on task context / 或让Qwen根据任务上下文自动委派
- Manage via `/agents` command in interactive mode / 在交互模式下通过`/agents`命令管理

> 📚 [Qwen SubAgents Docs](https://qwenlm.github.io/qwen-code-docs/en/users/features/sub-agents/)

</details>

<details>
<summary><strong>Kimi Code</strong></summary>

Agents are converted to Kimi Code CLI format (YAML + system prompt) and installed to `~/.config/kimi/agents/`.
智能体转换为Kimi Code CLI格式（YAML + 系统提示）并安装到`~/.config/kimi/agents/`。

```bash
# Convert and install / 转换和安装
./scripts/convert.sh --tool kimi
./scripts/install.sh --tool kimi
```

**Usage with Kimi Code: / 与Kimi Code一起使用：**
```bash
# Use an agent / 使用智能体
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml

# In a project / 在项目中
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml \
     --work-dir /your/project \
     "Review this React component"
```

See [integrations/kimi/README.md](integrations/kimi/README.md) for details.

</details>

---

### Regenerating After Changes / 更改后重新生成

When you add new agents or edit existing ones, regenerate all integration files:
当您添加新智能体或编辑现有智能体时，请重新生成所有集成文件：

```bash
./scripts/convert.sh                    # regenerate all (serial) / 重新生成所有（串行）
./scripts/convert.sh --parallel         # regenerate all in parallel (faster) / 并行重新生成所有（更快）
./scripts/convert.sh --tool cursor      # regenerate just one tool / 仅重新生成一个工具
```

---

## 🗺️ Roadmap / 路线图

- [ ] Interactive agent selector web tool / 交互式智能体选择器Web工具
- [x] Multi-agent workflow examples -- see [examples/](examples/) / 多智能体工作流示例 — 见[examples/](examples/)
- [x] Multi-tool integration scripts (Claude Code, GitHub Copilot, Antigravity, Gemini CLI, OpenCode, OpenClaw, Cursor, Aider, Windsurf, Qwen Code, Kimi Code) / 多工具集成脚本
- [ ] Video tutorials on agent design / 智能体设计视频教程
- [ ] Community agent marketplace / 社区智能体市场
- [ ] Agent "personality quiz" for project matching / 用于项目匹配的智能体"个性测验"
- [ ] "Agent of the Week" showcase series / "本周智能体"展示系列

---

## 🌐 Community Translations & Localizations / 社区翻译与本地化

Community-maintained translations and regional adaptations. These are independently maintained -- see each repo for coverage and version compatibility.
社区维护的翻译和区域适配。这些独立维护 — 请参阅每个仓库了解覆盖范围和版本兼容性。

| Language / 语言 | Maintainer / 维护者 | Link / 链接 | Notes / 备注 |
|----------|-----------|------|-------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 141 translated agents + 46 China-market originals / 141个翻译智能体 + 46个中国市场原创 |
| 🇨🇳 简体中文 (zh-CN) | [@dsclca12](https://github.com/dsclca12) | [agent-teams](https://github.com/dsclca12/agent-teams) | Independent translation with Bilibili, WeChat, Xiaohongshu localization / 独立翻译，含Bilibili、微信、小红书本地化 |

Want to add a translation? Open an issue and we'll link it here.
想添加翻译？提交issue，我们会在这里添加链接。

---

## 🔗 Related Resources / 相关资源

- [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) — Community-maintained OpenClaw agent collection (derived from this repo) / 社区维护的OpenClaw智能体集合（源自本仓库）

---

## 📜 License / 许可证

MIT License - Use freely, commercially or personally. Attribution appreciated but not required.
MIT许可证 — 自由使用，商业或个人用途均可。感谢署名，但非必需。

---

## 🙏 Acknowledgments / 致谢

What started as a Reddit thread about AI agent specialization has grown into something remarkable — **147 agents across 12 divisions**, supported by a community of contributors from around the world. Every agent in this repo exists because someone cared enough to write it, test it, and share it.

最初关于AI智能体专业化的Reddit讨论帖已经发展成为非凡的事物 — **跨越12个部门的147个智能体**，得到来自世界各地贡献者社区的支持。本仓库中的每个智能体之所以存在，是因为有人足够关心去编写、测试和分享它。

To everyone who has opened a PR, filed an issue, started a Discussion, or simply tried an agent and told us what worked — thank you. You're the reason The Agency keeps getting better.
向每个提交PR、提交issue、发起讨论或只是尝试智能体并告诉我们什么有效的人 — 感谢。您是The Agency不断进步的原因。

---

## 💬 Community / 社区

- **GitHub Discussions**: [Share your success stories](https://github.com/msitarzewski/agency-agents/discussions) / [分享您的成功故事](https://github.com/msitarzewski/agency-agents/discussions)
- **Issues**: [Report bugs or request features](https://github.com/msitarzewski/agency-agents/issues) / [报告bug或请求功能](https://github.com/msitarzewski/agency-agents/issues)
- **Reddit**: Join the conversation on r/ClaudeAI / 在r/ClaudeAI上加入讨论
- **Twitter/X**: Share with #TheAgency / 使用#TheAgency分享

---

## 🚀 Get Started / 开始使用

1. **Browse / 浏览** the agents above and find specialists for your needs / 上方的智能体并找到适合您需求的专家
2. **Copy / 复制** the agents to `~/.claude/agents/` for Claude Code integration / 将智能体复制到`~/.claude/agents/`以进行Claude Code集成
3. **Activate / 激活** agents by referencing them in your Claude conversations / 通过在Claude对话中引用智能体来激活
4. **Customize / 定制** agent personalities and workflows for your specific needs / 根据您的特定需求定制智能体个性和工作流程
5. **Share / 分享** your results and contribute back to the community / 分享您的结果并回馈社区

---

<div align="center">

**🎭 The Agency: Your AI Dream Team Awaits 🎭**
**🎭 The Agency: 您的AI梦之队正在等待 🎭**

[⭐ Star this repo](https://github.com/msitarzewski/agency-agents) • [🍴 Fork it](https://github.com/msitarzewski/agency-agents/fork) • [🐛 Report an issue](https://github.com/msitarzewski/agency-agents/issues) • [❤️ Sponsor](https://github.com/sponsors/msitarzewski)

Made with ❤️ by the community, for the community
由社区用爱制作，为社区服务

</div>
