<div align="center">

<img src="./static/image/MiroFish_logo_compressed.jpeg" alt="MiroFish Logo" width="75%"/>

<a href="https://trendshift.io/repositories/16144" target="_blank"><img src="https://trendshift.io/api/badge/repositories/16144" alt="666ghj%2FMiroFish | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

简洁通用的群体智能引擎，预测万物
</br>
<em>A Simple and Universal Swarm Intelligence Engine, Predicting Anything</em>

<a href="https://www.shanda.com/" target="_blank"><img src="./static/image/shanda_logo.png" alt="666ghj%2MiroFish | Shanda" height="40"/></a>

[![GitHub Stars](https://img.shields.io/github/stars/666ghj/MiroFish?style=flat-square&color=DAA520)](https://github.com/666ghj/MiroFish/stargazers)
[![GitHub Watchers](https://img.shields.io/github/watchers/666ghj/MiroFish?style=flat-square)](https://github.com/666ghj/MiroFish/watchers)
[![GitHub Forks](https://img.shields.io/github/forks/666ghj/MiroFish?style=flat-square)](https://github.com/666ghj/MiroFish/network)
[![Docker](https://img.shields.io/badge/Docker-Build-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/666ghj/MiroFish)

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=flat-square&logo=discord&logoColor=white)](http://discord.gg/ePf5aPaHnA)
[![X](https://img.shields.io/badge/X-Follow-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/mirofish_ai)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/mirofish_ai/)

[English](./README-EN.md) | [中文文档](./README.md)

</div>

## ⚡ Overview

**MiroFish** is a next-generation AI prediction engine powered by multi-agent technology. By extracting seed information from the real world (such as breaking news, policy drafts, or financial signals), it automatically constructs a high-fidelity parallel digital world. Within this space, thousands of intelligent agents with independent personalities, long-term memory, and behavioral logic freely interact and undergo social evolution. You can inject variables dynamically from a "God's-eye view" to precisely deduce future trajectories — **rehearse the future in a digital sandbox, and win decisions after countless simulations**.

> You only need to: Upload seed materials (data analysis reports or interesting novel stories) and describe your prediction requirements in natural language</br>
> MiroFish will return: A detailed prediction report and a deeply interactive high-fidelity digital world

### Our Vision

MiroFish is dedicated to creating a swarm intelligence mirror that maps reality. By capturing the collective emergence triggered by individual interactions, we break through the limitations of traditional prediction:

- **At the Macro Level**: We are a rehearsal laboratory for decision-makers, allowing policies and public relations to be tested at zero risk
- **At the Micro Level**: We are a creative sandbox for individual users — whether deducing novel endings or exploring imaginative scenarios, everything can be fun, playful, and accessible

From serious predictions to playful simulations, we let every "what if" see its outcome, making it possible to predict anything.

## 🌐 Live Demo

Welcome to visit our online demo environment and experience a prediction simulation on trending public opinion events we've prepared for you: [mirofish-live-demo](https://666ghj.github.io/mirofish-demo/)

## 📸 Screenshots

<div align="center">
<table>
<tr>
<td><img src="./static/image/Screenshot/运行截图1.png" alt="Screenshot 1" width="100%"/></td>
<td><img src="./static/image/Screenshot/运行截图2.png" alt="Screenshot 2" width="100%"/></td>
</tr>
<tr>
<td><img src="./static/image/Screenshot/运行截图3.png" alt="Screenshot 3" width="100%"/></td>
<td><img src="./static/image/Screenshot/运行截图4.png" alt="Screenshot 4" width="100%"/></td>
</tr>
<tr>
<td><img src="./static/image/Screenshot/运行截图5.png" alt="Screenshot 5" width="100%"/></td>
<td><img src="./static/image/Screenshot/运行截图6.png" alt="Screenshot 6" width="100%"/></td>
</tr>
</table>
</div>

## 🎬 Demo Videos

### 1. Wuhan University Public Opinion Simulation + MiroFish Project Introduction

<div align="center">
<a href="https://www.bilibili.com/video/BV1VYBsBHEMY/" target="_blank"><img src="./static/image/武大模拟演示封面.png" alt="MiroFish Demo Video" width="75%"/></a>

Click the image to watch the complete demo video for prediction using BettaFish-generated "Wuhan University Public Opinion Report"
</div>

### 2. Dream of the Red Chamber Lost Ending Simulation

<div align="center">
<a href="https://www.bilibili.com/video/BV1cPk3BBExq" target="_blank"><img src="./static/image/红楼梦模拟推演封面.jpg" alt="MiroFish Demo Video" width="75%"/></a>

Click the image to watch MiroFish's deep prediction of the lost ending based on hundreds of thousands of words from the first 80 chapters of "Dream of the Red Chamber"
</div>

> **Financial Prediction**, **Political News Prediction** and more examples coming soon...

## 🔄 Workflow

1. **Graph Building**: Seed extraction & Individual/collective memory injection & GraphRAG construction
2. **Environment Setup**: Entity relationship extraction & Persona generation & Agent configuration injection
3. **Simulation**: Dual-platform parallel simulation & Auto-parse prediction requirements & Dynamic temporal memory updates
4. **Report Generation**: ReportAgent with rich toolset for deep interaction with post-simulation environment
5. **Deep Interaction**: Chat with any agent in the simulated world & Interact with ReportAgent

## 🚀 Quick Start

### Option 1: Source Code Deployment (Recommended)

#### Prerequisites

| Tool | Version | Description | Check Installation |
|------|---------|-------------|-------------------|
| **Node.js** | 18+ | Frontend runtime, includes npm | `node -v` |
| **Python** | ≥3.11, ≤3.12 | Backend runtime | `python --version` |
| **uv** | Latest | Python package manager | `uv --version` |

#### 1. Configure Environment Variables

```bash
# Copy the example configuration file
cp .env.example .env

# Edit the .env file and fill in the required API keys
```

**Required Environment Variables:**

```env
# LLM API Configuration (supports any LLM API with OpenAI SDK format)
# Recommended: Alibaba Qwen-plus model via Bailian Platform: https://bailian.console.aliyun.com/
# High consumption, try simulations with fewer than 40 rounds first
LLM_API_KEY=your_api_key
LLM_BASE_URL=https://dashscope.aliyuncs.com/compatible-mode/v1
LLM_MODEL_NAME=qwen-plus

# Zep Cloud Configuration
# Free monthly quota is sufficient for simple usage: https://app.getzep.com/
ZEP_API_KEY=your_zep_api_key
```

#### 2. Install Dependencies

```bash
# One-click installation of all dependencies (root + frontend + backend)
npm run setup:all
```

Or install step by step:

```bash
# Install Node dependencies (root + frontend)
npm run setup

# Install Python dependencies (backend, auto-creates virtual environment)
npm run setup:backend
```

#### 3. Start Services

```bash
# Start both frontend and backend (run from project root)
npm run dev
```

**Service URLs:**
- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5001`

**Start Individually:**

```bash
npm run backend   # Start backend only
npm run frontend  # Start frontend only
```

### Option 2: Docker Deployment

```bash
# 1. Configure environment variables (same as source deployment)
cp .env.example .env

# 2. Pull image and start
docker compose up -d
```

Reads `.env` from root directory by default, maps ports `3000 (frontend) / 5001 (backend)`

> Mirror address for faster pulling is provided as comments in `docker-compose.yml`, replace if needed.

## 📖 Usage Guide

After starting the services, open `http://localhost:3000` in your browser and follow these steps:

### Step 1: Upload Seed Materials

On the right-side console of the home page:

1. **Upload files**: Drag and drop data analysis reports, news documents, or novels into the upload zone (supports **PDF, MD, TXT** formats, max 50 MB)
2. **Enter simulation prompt**: Describe your prediction requirement in natural language, e.g., *"What public sentiment would result if a certain announcement is released?"*
3. Click the **"Start Engine"** button

### Step 2: Graph Building

The system automatically:

- **Generates ontology**: The LLM analyzes your documents and extracts entity types and relation types
- **Builds GraphRAG**: Documents are chunked and injected into the Zep vector database to construct a knowledge graph

Click **"Enter Environment Setup"** when complete.

### Step 3: Environment Setup

The system automatically:

- **Generates Agent personas**: Extracts entities from the graph and generates a unique name, profession, bio, and interest topics for each Agent
- **Configures platform parameters**: The LLM intelligently configures dual-platform (Twitter-like / Reddit-like) simulation duration, rounds, and available actions

You can preview the generated Agent list before proceeding.

### Step 4: Run Simulation

- Agents interact in parallel on both platforms (Info Plaza / Topic Community)
- Real-time display of each platform's current round, elapsed time, and action count
- The graph panel dynamically visualizes the evolving knowledge graph

Click **"Start Generating Report"** when simulation completes.

### Step 5: Report Generation

The ReportAgent uses a rich toolset to deeply analyze simulation data and generates a prediction report section by section, including:

- Key findings and behavioral patterns
- Cross-platform analysis
- Prediction conclusions and recommendations

### Step 6: Deep Interaction

- **Chat with ReportAgent**: Ask questions about the report or explore findings further
- **Chat with simulated Agents**: Select any agent in the simulated world to learn about their behavior and thoughts during the simulation

> **Estimated time**: The full workflow takes approximately 15–45 minutes, depending on document size and simulation rounds.

## 🗂️ Project Structure

```
MiroFish/
├── backend/                  # Python Flask backend
│   ├── app/
│   │   ├── api/              # API endpoints (graph / simulation / report)
│   │   ├── services/         # Core business logic (13 service modules)
│   │   ├── models/           # Data models
│   │   ├── utils/            # Utilities (LLM client, file parser, etc.)
│   │   └── config.py         # Configuration management
│   ├── scripts/              # Utility scripts
│   ├── run.py                # Backend entry point
│   └── pyproject.toml        # Python dependencies
├── frontend/                 # Vue 3 + Vite frontend
│   ├── src/
│   │   ├── views/            # Page components
│   │   ├── components/       # UI components (5 step components + graph panel)
│   │   ├── api/              # API call modules
│   │   ├── router/           # Router configuration
│   │   └── store/            # State management
│   └── package.json          # Frontend dependencies
├── docker-compose.yml        # Docker Compose configuration
├── Dockerfile                # Multi-stage Docker build
├── .env.example              # Environment variable template
└── package.json              # Root scripts (monorepo management)
```

## ⚙️ Configuration Reference

### Required Environment Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `LLM_API_KEY` | LLM API key (any OpenAI SDK-compatible API) | `sk-xxxxxxxx` |
| `LLM_BASE_URL` | LLM API base URL | `https://dashscope.aliyuncs.com/compatible-mode/v1` |
| `LLM_MODEL_NAME` | Model name | `qwen-plus` |
| `ZEP_API_KEY` | Zep Cloud API key | `z_xxxxxxxx` |

### Optional Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `LLM_BOOST_API_KEY` | Boost LLM key (omit from `.env` if unused) | — |
| `LLM_BOOST_BASE_URL` | Boost LLM base URL | — |
| `LLM_BOOST_MODEL_NAME` | Boost LLM model name | — |
| `FLASK_DEBUG` | Flask debug mode | `True` |
| `OASIS_DEFAULT_MAX_ROUNDS` | Default max simulation rounds | `10` |
| `REPORT_AGENT_MAX_TOOL_CALLS` | Max tool calls for ReportAgent | `5` |
| `REPORT_AGENT_MAX_REFLECTION_ROUNDS` | Max reflection rounds for ReportAgent | `2` |
| `REPORT_AGENT_TEMPERATURE` | ReportAgent generation temperature | `0.5` |

## 🔧 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| `LLM_API_KEY 未配置` on startup | `.env` file missing or keys not set | Run `cp .env.example .env` and fill in API keys |
| `uv` command not found | Python package manager uv not installed | See [uv installation docs](https://docs.astral.sh/uv/getting-started/installation/) |
| Blank frontend page | Node.js version too old | Ensure Node.js ≥ 18; check with `node -v` |
| LLM requests fail during simulation | API quota exhausted or network issue | Check LLM API balance; try simulations with < 40 rounds first |
| Slow Docker image pull | Slow access to GitHub Container Registry | Replace with the mirror address in `docker-compose.yml` |
| File upload fails | Unsupported format or exceeds 50 MB | Ensure file is PDF, MD, or TXT and under 50 MB |

## 📬 Join the Conversation

<div align="center">
<img src="./static/image/QQ群.png" alt="QQ Group" width="60%"/>
</div>

&nbsp;

The MiroFish team is recruiting full-time/internship positions. If you're interested in multi-agent simulation and LLM applications, feel free to send your resume to: **mirofish@shanda.com**

## 📄 Acknowledgments

**MiroFish has received strategic support and incubation from Shanda Group!**

MiroFish's simulation engine is powered by **[OASIS (Open Agent Social Interaction Simulations)](https://github.com/camel-ai/oasis)**, We sincerely thank the CAMEL-AI team for their open-source contributions!

## 📈 Project Statistics

<a href="https://www.star-history.com/#666ghj/MiroFish&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=666ghj/MiroFish&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=666ghj/MiroFish&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=666ghj/MiroFish&type=date&legend=top-left" />
 </picture>
</a>