````markdown
# agent-zoo

A collection of real-world and representative agentic systems for security testing.

## Purpose

This repo exists to test and evaluate security products for agentic systems.

It provides a set of agent implementations, workflows, and tool-using applications that can be used to:

- simulate real agent behavior
- test security controls
- reproduce agent failure cases
- benchmark detection and enforcement

## What is inside

Each folder contains one agentic system or workflow, such as:

- single-agent apps
- tool-using agents
- RAG agents
- browser agents
- coding agents
- multi-agent systems
- framework-specific examples

## Example structure

```text
agent-zoo/
├── 00-langgraph-production/
├── 01-react-tool-agent/
├── 02-langchain-rag-agent/
├── 03-langgraph-supervisor/
├── 04-crewai-research-crew/
├── 05-openai-assistants-parallel/
├── 06-autogen-code-executor/
├── 07-langgraph-memory-agent/
├── 08-typescript-browser-agent/
├── 09-multi-agent-pipeline-fastapi/
├── 10-rust-agent-runtime/
├── 11-smolagents-computer-use/
└── 12-heterogeneous-multi-framework/
````

## Use cases

Use this repo to:

* run security scans against agent systems
* test policy enforcement
* validate runtime controls
* reproduce unsafe agent actions
* compare behavior across frameworks

## How to use

Clone the repo:

```bash
git clone <repo-url>
cd agent-zoo
```

Run or inspect any example system from its folder.

## Notes

* This repo is for testing and research.
* Some examples may require API keys or local setup.
* Each project keeps its own dependencies and runtime model.

## Goal

Make agent security testing practical, repeatable, and grounded in real agent systems.

```
```
