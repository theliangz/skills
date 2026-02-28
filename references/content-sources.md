# 内容资源获取指南

## 概述

本指南详细说明如何从 AlphaXiv、AIHot、GitHub 三大平台自动获取创作素材。

## 一、AlphaXiv 论文获取

### 平台信息

- **网址**: https://www.alphaxiv.org/
- **用途**: 优秀论文分享系列素材来源
- **更新频率**: 实时更新

### 获取流程

#### Step 1: 访问并获取论文列表

使用 webReader 工具获取首页内容：

```
URL: https://www.alphaxiv.org/
```

#### Step 2: 筛选相关论文

从获取的论文列表中，筛选包含以下关键词的论文：

| 类别 | 关键词 |
|------|--------|
| **大模型** | LLM, Large Language Model, GPT, Claude, LLaMA, Gemma, Mistral, Qwen, DeepSeek, GLM |
| **Agent** | Agent, Multi-Agent, Autonomous Agent, Tool Use, Function Calling, Planning, ReAct, ToT |
| **训练方法** | Fine-tuning, RLHF, DPO, PPO, SFT, Pre-training, Post-training |
| **推理方法** | Reasoning, Chain-of-Thought, CoT, Tree-of-Thoughts, ToT, Self-Consistency |
| **架构** | Transformer, Attention, Mamba, RWKV, State Space Model, MoE, Mixture of Experts |
| **应用** | RAG, Retrieval, Embedding, Vector Database, Long Context, Multimodal |

#### Step 3: 价值评估

对筛选出的论文进行价值评估，优先选择符合以下条件的：

1. **发表来源**: NeurIPS, ICML, ICLR, ACL, EMNLP 等顶会
2. **作者团队**: OpenAI, Anthropic, Google DeepMind, Meta AI, Microsoft Research 等
3. **技术创新**: 有明显的架构或方法创新
4. **工程价值**: 可落地、可复现、有实际应用价值
5. **热度指标**: 在 AlphaXiv 上有较高讨论度

#### Step 4: 解析论文内容

获取论文详情后，解析以下信息：

- **论文标题**: 中英文对照
- **作者及机构**
- **发表来源**: arXiv ID / 会议名称
- **核心问题**: 论文解决什么问题
- **核心方法**: 提出的方法/架构
- **关键创新**: 1-3 点核心创新
- **实验结果**: 关键性能指标
- **SOTA 对比**: 与现有方法对比

#### Step 5: 推荐选题

根据解析结果，推荐 1 篇最具解读价值的论文，理由：

- 技术前沿性
- 读者关注度
- 解读可行性

---

## 二、AIHot 新闻获取

### 平台信息

- **网址**: https://aihot.today/
- **用途**: AI快讯分享系列素材来源
- **更新频率**: 每日更新

### 获取流程

#### Step 1: 获取今日热点

使用 webReader 工具获取今日热门 AI 新闻：

```
URL: https://aihot.today/
```

#### Step 2: 分类筛选

将新闻按类别分类：

| 类别 | 关键词 | 优先级 |
|------|--------|--------|
| **产品发布** | 发布, 上线, 开放, Launch, Release | ⭐⭐⭐⭐⭐ |
| **模型更新** | 升级, 更新, 迭代, 新版本 | ⭐⭐⭐⭐⭐ |
| **论文突破** | 论文, 研究, 突破, SOTA | ⭐⭐⭐⭐ |
| **开源项目** | 开源, GitHub, 开放源码 | ⭐⭐⭐ |
| **行业动态** | 融资, 收购, 合作, 政策 | ⭐⭐ |
| **技术趋势** | 趋势, 方向, 预测 | ⭐⭐ |

#### Step 3: 价值判断

对每条新闻进行价值判断：

1. **时效性**: 是否为今日/最新消息
2. **影响力**: 对行业/开发者的影响程度
3. **相关性**: 与公众号定位的契合度
4. **独家性**: 是否为独家/首发消息
5. **讨论度**: 社交媒体讨论热度

#### Step 4: 推荐选题

选择 1-2 条最具新闻价值的选题，优先考虑：

- **重大产品发布**: GPT-X, Claude X, 新模型发布
- **技术突破**: 新架构、新方法、新纪录
- **行业事件**: 重大融资、收购、合作

---

## 三、GitHub 项目获取

### 平台信息

- **网址**: https://github.com/trending
- **用途**: 开源项目实战系列素材来源
- **更新频率**: 每日更新

### 获取流程

#### Step 1: 获取趋势列表

使用 webReader 工具获取 trending 列表：

```
URL: https://github.com/trending
```

#### Step 2: 语言筛选

关注以下编程语言的项目：

| 语言 | 相关性 |
|------|--------|
| Python | ⭐⭐⭐⭐⭐ |
| Jupyter Notebook | ⭐⭐⭐⭐⭐ |
| TypeScript | ⭐⭐⭐⭐ |
| Rust | ⭐⭐⭐ |

#### Step 3: 主题筛选

筛选与以下主题相关的项目：

| 主题 | 关键词 |
|------|--------|
| **LLM** | llm, gpt, claude, llama, mistral, inference, training |
| **Agent** | agent, autonomous, tool-use, multi-agent |
| **RAG** | rag, retrieval, vector, embedding, langchain, llama-index |
| **框架** | framework, library, api, sdk |
| **工具** | tool, utility, cli, gui |

#### Step 4: 项目评估

对项目进行全面评估：

1. **Stars 数量**: > 1000 为佳
2. **增长速度**: 近期 stars 增长趋势
3. **活跃度**: Recent commits, issues, PRs
4. **文档质量**: README 完整度、文档清晰度
5. **技术栈**: Python/TypeScript 优先
6. **可复现性**: 是否易于安装运行
7. **实战价值**: 是否有实际应用场景

#### Step 5: 项目分析

对选定的项目进行深入分析：

- **项目简介**: 一句话概括项目功能
- **核心特性**: 3-5 点核心功能
- **技术栈**: 主要依赖和框架
- **架构设计**: 项目整体架构
- **使用场景**: 适用场景和用户群体
- **安装方法**: 快速开始步骤
- **示例代码**: 核心代码片段

#### Step 6: 推荐选题

推荐 1 个最具实战价值的项目，确保：

- 有清晰的文档
- 代码可运行
- 有实际应用价值
- 适合技术文章解读

---

## 四、用户指令处理

### 常见指令类型

| 指令示例 | 意图 | 动作 |
|----------|------|------|
| "今日创作选题" | 获取所有平台热点 | 遍历三大平台，推荐选题 |
| "今天的 AI 热点" | 获取 AIHot 新闻 | 访问 AIHot，推荐 1-2 条 |
| "最新 Agent 论文" | 获取 AlphaXiv 论文 | 访问 AlphaXiv，筛选 Agent 论文 |
| "热门 AI 项目" | 获取 GitHub 项目 | 访问 GitHub Trending，筛选 AI 项目 |
| "写一篇论文解读" | 基于论文创作 | 获取论文 → 创作 |
| "写一篇 AI 快讯" | 基于新闻创作 | 获取新闻 → 创作 |
| "写一篇项目实战" | 基于项目创作 | 获取项目 → 创作 |

### 处理流程

```
用户指令
    ↓
解析意图（获取素材 vs 直接创作）
    ↓
确定系列类型
    ↓
访问对应平台
    ↓
筛选内容
    ↓
推荐选题 / 直接创作
```

---

## 五、输出格式

### 选题推荐格式

当用户要求推荐选题时，按以下格式输出：

```
## 今日推荐选题

### 1. 【系列】选题名称
- **来源**: AlphaXiv / AIHot / GitHub
- **链接**: 原文链接
- **推荐理由**: 2-3 句说明价值
- **核心亮点**: 3-5 点要点

### 2. 【系列】选题名称
...
```

### 创作完成格式

当直接完成创作时，输出完整文章，格式符合对应系列模板。
