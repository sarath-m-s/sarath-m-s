<h1 align="center">Hi, I'm Sarath 👋</h1>
<h3 align="center">AI Engineer · Agentic Systems & LLM Infrastructure</h3>

<p align="center">
  <a href="https://linkedin.com/in/iamsarathms"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="mailto:sarathms789@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
  <img src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="aws-saa"/>
</p>

---

I build **production AI agents and the infrastructure they run on** — multi-agent orchestration, LLM context-management systems, and serverless platforms on AWS. Currently an Associate Software Engineer at **KeyValue Software Systems**, working on an AI-powered learning platform where I ship real-time tutoring agents, knowledge-graph workflows, and high-concurrency backends.

My interest is **infrastructure-level AI tooling** rather than application-layer demos: reliability, determinism, cost control, and observability for agent systems.

### What I work on

- 🤖 **Agentic systems** — LangGraph / LangChain agents, human-in-the-loop workflows, multi-agent orchestration
- 🧠 **LLM infrastructure** — context-window management, streaming inference, RAG, knowledge graphs, MCP
- ☁️ **Serverless AWS** — Bedrock AgentCore, Lambda, Step Functions, API Gateway, Terraform IaC
- ⚡ **High-concurrency backends** — FastAPI + Redis services handling 5,000+ concurrent users

---

### 🚀 Featured Projects

**[l1-pager](https://github.com/sarath-m-s)** — *Virtual memory for LLM context windows*
A drop-in `BaseChatModel` wrapper that pages out large/stale tool results and demand-pages them back when the model asks. Importance-scored eviction (LRU / HYBRID), Redis or in-memory heap, deterministic page IDs for idempotent retries. Published on **PyPI** (`l1-pager`) and **npm** (`l1-pager-core`).
`Python · LangChain · LangGraph · Redis`

**Data Migration Agent Suite** — *Multi-tenant agent platform on AWS Bedrock AgentCore*
A reusable agent platform (Python SDK, 18 Terraform modules, Next.js 14 control plane) plus a five-agent pipeline that takes a source database to a fully sequenced migration plan. Cut new-agent time-to-production from weeks to a single PR.
`Bedrock AgentCore · LangGraph · Terraform · Next.js · S3 Vectors`

**SQL Agent & Bedrock Tooling** — *Natural-language → SQL automation*
LLM-powered NL→SQL pipeline with secure Bedrock inference and an automated deployment pipeline that took setup from 3 days to 15 minutes.
`Python · AWS Bedrock · SQL`

**Ghost Pulse** — *Privacy-first developer-productivity CLI*
Passively observes shell activity, git events, and file changes to surface toil patterns. Local-first with RAG-powered error-fix suggestions over a SQLite vector store.
`Python · SQLite · RAG`

---

### 🛠️ Tech Stack

**AI / LLM**

<p align="left">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="langchain"/>
  <img src="https://img.shields.io/badge/LangGraph-FF6F61?style=for-the-badge&logo=langgraph&logoColor=white" alt="langgraph"/>
  <img src="https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="bedrock"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="mcp"/>
  <img src="https://img.shields.io/badge/RAG-5A67D8?style=for-the-badge&logoColor=white" alt="rag"/>
</p>

**Languages & Backend**

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="typescript"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="fastapi"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="nodejs"/>
</p>

**Frontend**

<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="react"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="nextjs"/>
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="react-native"/>
</p>

**Cloud & Infrastructure**

<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="aws"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="terraform"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="gh-actions"/>
</p>

**Databases**

<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="postgres"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="redis"/>
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" alt="dynamodb"/>
  <img src="https://img.shields.io/badge/pgvector-008bb9?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector"/>
</p>
