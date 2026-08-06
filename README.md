# Agent Frameworks

A curated list of popular **AI agent frameworks and SDKs**, grouped by ecosystem.
Every entry links to its GitHub repository and shows a **live star badge**.


## Contents

- [General-purpose & multi-agent orchestration](#general-purpose--multi-agent-orchestration)
- [Autonomous "AutoGPT-style" agents](#autonomous-autogpt-style-agents)
- [Low-code & visual builders](#low-code--visual-builders)
- [JavaScript / TypeScript](#javascript--typescript)
- [JVM (Java / Kotlin)](#jvm-java--kotlin)
- [Go](#go)
- [Rust](#rust)
- [Coding agents](#coding-agents)
- [Browser & computer use](#browser--computer-use)
- [Voice & real-time](#voice--real-time)
- [Agent infrastructure (tools · memory · sandboxes)](#agent-infrastructure-tools--memory--sandboxes)

---

## General-purpose & multi-agent orchestration

| Framework | Stars | Lang | What it is |
| --- | --- | --- | --- |
| [LangChain](https://github.com/langchain-ai/langchain) | ![](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square) | Python | Composable framework for LLM apps with a huge tool/integration ecosystem |
| [LangGraph](https://github.com/langchain-ai/langgraph) | ![](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square) | Python | Stateful, graph-based multi-agent orchestration with human-in-the-loop |
| [LlamaIndex](https://github.com/run-llama/llama_index) | ![](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square) | Python | Data framework for RAG and agentic workflows |
| [Microsoft AutoGen](https://github.com/microsoft/autogen) | ![](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square) | Python/.NET | Multi-agent conversation framework |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | ![](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=flat-square) | C#/Py/Java | Enterprise agent SDK with plugins and invocation filters |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) | ![](https://img.shields.io/github/stars/microsoft/agent-framework?style=flat-square) | .NET/Python | Unified successor to Semantic Kernel + AutoGen |
| [CrewAI](https://github.com/crewAIInc/crewAI) | ![](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square) | Python | Role-playing multi-agent "crews" and flows |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | ![](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square) | Python | Lightweight agents with handoffs and guardrails |
| [OpenAI Swarm](https://github.com/openai/swarm) | ![](https://img.shields.io/github/stars/openai/swarm?style=flat-square) | Python | Experimental/educational lightweight multi-agent orchestration |
| [Google ADK](https://github.com/google/adk-python) | ![](https://img.shields.io/github/stars/google/adk-python?style=flat-square) | Python | Google's model-agnostic Agent Development Kit |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | ![](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=flat-square) | Python | Type-safe agent framework from the Pydantic team |
| [Haystack](https://github.com/deepset-ai/haystack) | ![](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square) | Python | Production LLM/RAG and agent pipelines (deepset) |
| [Agno](https://github.com/agno-agi/agno) | ![](https://img.shields.io/github/stars/agno-agi/agno?style=flat-square) | Python | High-performance multi-modal agents (formerly Phidata) |
| [CAMEL](https://github.com/camel-ai/camel) | ![](https://img.shields.io/github/stars/camel-ai/camel?style=flat-square) | Python | Research framework for multi-agent societies |
| [DSPy](https://github.com/stanfordnlp/dspy) | ![](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square) | Python | Program (don't prompt) LMs — optimizers and compilers |
| [smolagents](https://github.com/huggingface/smolagents) | ![](https://img.shields.io/github/stars/huggingface/smolagents?style=flat-square) | Python | Minimal, code-first agents (Hugging Face) |
| [Letta](https://github.com/letta-ai/letta) | ![](https://img.shields.io/github/stars/letta-ai/letta?style=flat-square) | Python | Stateful agents with long-term memory (formerly MemGPT) |
| [Langroid](https://github.com/langroid/langroid) | ![](https://img.shields.io/github/stars/langroid/langroid?style=flat-square) | Python | Multi-agent programming framework |
| [Griptape](https://github.com/griptape-ai/griptape) | ![](https://img.shields.io/github/stars/griptape-ai/griptape?style=flat-square) | Python | Modular agents, pipelines, and workflows |
| [Marvin](https://github.com/PrefectHQ/marvin) | ![](https://img.shields.io/github/stars/PrefectHQ/marvin?style=flat-square) | Python | Lightweight AI engineering toolkit (Prefect) |
| [Strands Agents](https://github.com/strands-agents/sdk-python) | ![](https://img.shields.io/github/stars/strands-agents/sdk-python?style=flat-square) | Python | Model-driven agent SDK (AWS) |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | ![](https://img.shields.io/github/stars/BrainBlend-AI/atomic-agents?style=flat-square) | Python | Lightweight, composable "atomic" building blocks |
| [AWS Agent Squad](https://github.com/awslabs/agent-squad) | ![](https://img.shields.io/github/stars/awslabs/agent-squad?style=flat-square) | Python/TS | Multi-agent orchestrator (formerly Multi-Agent Orchestrator) |
| [BeeAI Framework](https://github.com/i-am-bee/beeai-framework) | ![](https://img.shields.io/github/stars/i-am-bee/beeai-framework?style=flat-square) | Python/TS | Production agents (IBM · Linux Foundation) |
| [Julep](https://github.com/julep-ai/julep) | ![](https://img.shields.io/github/stars/julep-ai/julep?style=flat-square) | Python | Serverless platform + SDK for stateful agents |

## Autonomous "AutoGPT-style" agents

| Framework | Stars | Lang | What it is |
| --- | --- | --- | --- |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ![](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square) | Python | Pioneering autonomous GPT agent platform |
| [MetaGPT](https://github.com/geekan/MetaGPT) | ![](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square) | Python | Multi-agent "software company" framework |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | ![](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=flat-square) | Python | Minimal task-driven autonomous agent |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | ![](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat-square) | Python | Dev-first autonomous agent framework |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | ![](https://img.shields.io/github/stars/reworkd/AgentGPT?style=flat-square) | TypeScript | Browser-based autonomous agents |

## Low-code & visual builders

| Framework | Stars | Lang | What it is |
| --- | --- | --- | --- |
| [Dify](https://github.com/langgenius/dify) | ![](https://img.shields.io/github/stars/langgenius/dify?style=flat-square) | Python/TS | Open-source LLM app & agent platform |
| [Flowise](https://github.com/FlowiseAI/Flowise) | ![](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=flat-square) | TypeScript | Drag-and-drop LLM/agent builder |
| [Langflow](https://github.com/langflow-ai/langflow) | ![](https://img.shields.io/github/stars/langflow-ai/langflow?style=flat-square) | Python | Visual builder for agent flows |
| [n8n](https://github.com/n8n-io/n8n) | ![](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square) | TypeScript | Workflow automation with native AI agent nodes |
| [Rivet](https://github.com/Ironclad/rivet) | ![](https://img.shields.io/github/stars/Ironclad/rivet?style=flat-square) | TypeScript | Visual programming environment for AI agents |
| [Rasa](https://github.com/RasaHQ/rasa) | ![](https://img.shields.io/github/stars/RasaHQ/rasa?style=flat-square) | Python | Open-source conversational AI / assistants |

## JavaScript / TypeScript

| Framework | Stars | What it is |
| --- | --- | --- |
| [LangChain.js](https://github.com/langchain-ai/langchainjs) | ![](https://img.shields.io/github/stars/langchain-ai/langchainjs?style=flat-square) | JS/TS port of LangChain |
| [Vercel AI SDK](https://github.com/vercel/ai) | ![](https://img.shields.io/github/stars/vercel/ai?style=flat-square) | TS toolkit for AI apps/agents with UI streaming |
| [Mastra](https://github.com/mastra-ai/mastra) | ![](https://img.shields.io/github/stars/mastra-ai/mastra?style=flat-square) | TS agent framework — workflows, memory, RAG |
| [VoltAgent](https://github.com/voltagent/voltagent) | ![](https://img.shields.io/github/stars/voltagent/voltagent?style=flat-square) | TS agent framework with built-in observability |
| [OpenAI Agents JS](https://github.com/openai/openai-agents-js) | ![](https://img.shields.io/github/stars/openai/openai-agents-js?style=flat-square) | Official JS/TS Agents SDK |
| [Inngest AgentKit](https://github.com/inngest/agent-kit) | ![](https://img.shields.io/github/stars/inngest/agent-kit?style=flat-square) | Multi-agent networks on durable workflows |

## JVM (Java / Kotlin)

| Framework | Stars | What it is |
| --- | --- | --- |
| [LangChain4j](https://github.com/langchain4j/langchain4j) | ![](https://img.shields.io/github/stars/langchain4j/langchain4j?style=flat-square) | LangChain for Java |
| [Spring AI](https://github.com/spring-projects/spring-ai) | ![](https://img.shields.io/github/stars/spring-projects/spring-ai?style=flat-square) | Spring-native AI/agent framework |
| [Google ADK (Java)](https://github.com/google/adk-java) | ![](https://img.shields.io/github/stars/google/adk-java?style=flat-square) | Agent Development Kit for the JVM |

## Go

| Framework | Stars | What it is |
| --- | --- | --- |
| [Eino](https://github.com/cloudwego/eino) | ![](https://img.shields.io/github/stars/cloudwego/eino?style=flat-square) | Go LLM/agent framework (CloudWeGo · ByteDance) |
| [Genkit](https://github.com/firebase/genkit) | ![](https://img.shields.io/github/stars/firebase/genkit?style=flat-square) | Cross-language agent framework (Go/JS/Python, Google) |
| [LangChainGo](https://github.com/tmc/langchaingo) | ![](https://img.shields.io/github/stars/tmc/langchaingo?style=flat-square) | LangChain for Go |

## Rust

| Framework | Stars | What it is |
| --- | --- | --- |
| [Rig](https://github.com/0xPlaygrounds/rig) | ![](https://img.shields.io/github/stars/0xPlaygrounds/rig?style=flat-square) | Rust framework for LLM-powered agents |

## Coding agents

| Framework | Stars | What it is |
| --- | --- | --- |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | ![](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square) | Autonomous software-engineering agents (formerly OpenDevin) |
| [Aider](https://github.com/Aider-AI/aider) | ![](https://img.shields.io/github/stars/Aider-AI/aider?style=flat-square) | AI pair programming in your terminal |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | ![](https://img.shields.io/github/stars/SWE-agent/SWE-agent?style=flat-square) | Agents that resolve real GitHub issues (Princeton) |
| [gpt-engineer](https://github.com/gpt-engineer-org/gpt-engineer) | ![](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer?style=flat-square) | Build codebases from a natural-language prompt |
| [Potpie](https://github.com/potpie-ai/potpie) | ![](https://img.shields.io/github/stars/potpie-ai/potpie?style=flat-square) | Custom engineering agents for your codebase |

## Browser & computer use

| Framework | Stars | What it is |
| --- | --- | --- |
| [Browser Use](https://github.com/browser-use/browser-use) | ![](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square) | Let agents drive a real browser |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | ![](https://img.shields.io/github/stars/Skyvern-AI/skyvern?style=flat-square) | Automate browser workflows with LLMs + vision |
| [Stagehand](https://github.com/browserbase/stagehand) | ![](https://img.shields.io/github/stars/browserbase/stagehand?style=flat-square) | AI browser automation (Browserbase) |

## Voice & real-time

| Framework | Stars | What it is |
| --- | --- | --- |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | ![](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat-square) | Real-time voice & multimodal agents |
| [LiveKit Agents](https://github.com/livekit/agents) | ![](https://img.shields.io/github/stars/livekit/agents?style=flat-square) | Realtime voice/video agents over WebRTC |
| [Parlant](https://github.com/emcie-co/parlant) | ![](https://img.shields.io/github/stars/emcie-co/parlant?style=flat-square) | Controllable, guideline-driven conversational agents |

## Agent infrastructure (tools · memory · sandboxes)

| Project | Stars | What it is |
| --- | --- | --- |
| [Composio](https://github.com/ComposioHQ/composio) | ![](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat-square) | Tooling/integration layer — hundreds of tools for agents |
| [E2B](https://github.com/e2b-dev/E2B) | ![](https://img.shields.io/github/stars/e2b-dev/E2B?style=flat-square) | Secure cloud sandboxes for AI code execution |
| [Mem0](https://github.com/mem0ai/mem0) | ![](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square) | Memory layer for agents |
| [Semantic Router](https://github.com/aurelio-labs/semantic-router) | ![](https://img.shields.io/github/stars/aurelio-labs/semantic-router?style=flat-square) | Fast routing/decision layer for agents |

---

### Adding an entry

1. Drop the framework in the most fitting section (keep rows roughly ordered by relevance).
2. Link the name to the GitHub repo: `[Name](https://github.com/<owner>/<repo>)`.
3. Add the live star badge: `![](https://img.shields.io/github/stars/<owner>/<repo>?style=flat-square)`.
> **Stars are dynamic.** Each badge is a [shields.io](https://shields.io) query
> against the GitHub API (`img.shields.io/github/stars/<owner>/<repo>`), so counts
> refresh on every page view — no manual updates needed. Moved repos resolve through
> GitHub's redirect.
Categories overlap — a framework is listed once, in its primary home.
