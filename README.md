<div align="center">

<img src="./assets/jojo-ai-banner.png" width="100%" alt="AI Engineer Banner" />

# AI Engineer

`Agent` · `RAG` · `LLM` · `NLP` · `Python Backend`

`Shanghai, China`

</div>

---

## 👋 关于我

- 🎓 计算机相关专业，持续补强计算机基础与 AI 工程能力
- 🤖 当前重点方向：Agent、RAG、LLM 应用开发、NLP 与 AI 后端

---

## 🧭 当前技术方向

| 方向 | 学习与实践内容 |
|---|---|
| 🤖 Agent | LangGraph、Tool Calling、MCP、Memory、多 Agent、Workflow、任务规划 |
| 🔎 RAG | 文档解析、父子切分、BM25、Dense / Sparse Hybrid Search、Reranker、RAG Evaluation |
| 💬 LLM 应用 | Prompt、结构化输出、多轮会话、Session、缓存、引用溯源、拒答 |
| 🧠 NLP | Transformer、BERT、MacBERT、NER、Token Classification、模型评估 |
| ⚙️ AI 后端 | FastAPI、Pydantic、Redis、MySQL、Milvus、OpenSearch、Docker |

---

## 🛠️ 技术栈

### Agent / LLM

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C1C1C?style=flat-square" />
  <img src="https://img.shields.io/badge/MCP-6F42C1?style=flat-square" />
  <img src="https://img.shields.io/badge/Agent-7048E8?style=flat-square" />
  <img src="https://img.shields.io/badge/LLM-4C6EF5?style=flat-square" />
  <img src="https://img.shields.io/badge/RAG-0B7285?style=flat-square" />
</p>

### Retrieval / RAG

<p>
  <img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square" />
  <img src="https://img.shields.io/badge/BM25-495057?style=flat-square" />
  <img src="https://img.shields.io/badge/BGE--M3-364FC7?style=flat-square" />
  <img src="https://img.shields.io/badge/BGE--Reranker-5F3DC4?style=flat-square" />
</p>

### AI / NLP

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/MacBERT-7950F2?style=flat-square" />
</p>

### Backend / Data

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square" />
</p>

### Engineering

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white" />
</p>

---

## 🚀 项目与实践

### 🏦 聚源洞见 · 多 Agent 智能投研系统

> 面向证券、基金与财富管理场景的多 Agent 投研系统，结合结构化金融数据、知识检索、任务规划与合规控制。

**主要工作：**

- 基于 `LangGraph` 设计 Orchestrator 编排层，实现简单 Workflow 与复杂任务动态规划
- 设计 Data Agent、Portfolio Agent、Compliance Agent 等核心 Agent
- Data Agent 通过 MCP、AIDB 与内部接口获取结构化金融数据
- 支持结构化查询、非结构化检索、组合诊断、报表生成等任务
- 使用 State + Checkpointer 实现任务状态管理与断点续跑
- 设计短期记忆与长期偏好记忆机制
- 建立 L0 / L1 / L2 / L3 合规分级、权限控制与人工审核流程
- 支持异常重试、超时降级、多用户任务隔离与审计日志

**Tech Stack**

`Python` `FastAPI` `Pydantic` `LangGraph` `MCP` `Redis` `MySQL` `Milvus` `OpenSearch` `Docker`

---

### 📊 WarrenQ · 财报 / 公告智能问答系统

> 面向证券研究员、投顾与金融分析场景的 RAG 智能问答系统，支持财报、公告等复杂金融文档检索。

**主要工作：**

- 使用 `pdfplumber` 解析 PDF 文本层，异常文档回退 PaddleOCR / PP-Structure
- 基于标题层级与文档结构进行 Parent-Child Chunking
- 使用 BGE-M3 构建 Dense / Sparse 向量表示
- Milvus 负责向量检索，OpenSearch BM25 负责关键词检索
- 使用 RRF 融合多路召回结果
- 使用 BGE-Reranker 进行精排
- 支持 Query Rewrite、HyDE、子查询拆分等检索策略
- 金融指标通过 MySQL / 内部结构化数据库直接查询
- 使用 Redis 缓存热点 Query 与检索结果
- 建立 Recall@K、MRR、NDCG、RAGAS、Citation 等评测体系

**Tech Stack**

`Python` `FastAPI` `Milvus` `OpenSearch` `Redis` `MySQL` `BGE-M3` `BGE-Reranker` `PaddleOCR` `Docker`

---

### 🧠 中文金融细粒度命名实体识别

> 面向银行借贷与金融评论文本的细粒度 NER 系统。

**主要工作：**

- 构建字符级 BIO 标注体系
- 设计 Token 与原始字符标签对齐算法
- 以 `bert-base-chinese` 构建基线模型
- 引入 `MacBERT` 作为最终编码器
- 使用 PyTorch + Transformers 完成 Token Classification
- 使用 AdamW 进行模型训练
- 使用 Precision / Recall / F1 评估实体识别效果
- 使用 seqeval 进行序列标注评测
- 尝试知识蒸馏与模型压缩优化

**实体类型**

`BANK` `PRODUCT` `COMMENTS_N` `COMMENTS_ADJ`

**Tech Stack**

`Python` `PyTorch` `Transformers` `MacBERT` `seqeval`

---

## 📖 正在学习

```text
Agent
├── LangGraph
├── Multi-Agent
├── Tool Calling
├── MCP
├── Memory
├── Workflow
└── Agent Evaluation

RAG
├── Hybrid Retrieval
├── Parent-Child Retrieval
├── Reranker
├── Recall@K
├── MRR
├── NDCG
└── Badcase Analysis

LLM Engineering
├── Prompt Engineering
├── Structured Output
├── Context Engineering
├── Session Management
└── LLM Evaluation

AI Backend
├── FastAPI
├── async / await
├── Redis
├── MySQL
├── Milvus
├── Docker
└── Deployment
