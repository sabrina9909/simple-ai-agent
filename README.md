# Simple AI Assistant (LangChain + LangGraph)

An interactive terminal-based AI agent built with **LangChain**, **LangGraph**, and **OpenAI GPT models**.  
This project demonstrates how to combine reasoning, tools, and language models in one minimal example.

---

## Features
- Chat interactively with an OpenAI-powered model
- Use a custom calculator tool (`@tool` decorator)
- Modular design for adding new tools easily

---

## Installation


```bash
git clone https://github.com/<your-username>/simple-ai-agent.git
cd simple-ai-agent

python -m venv .venv
.venv\Scripts\activate   # On Windows

pip install -r requirements.txt
### or
uv sync

OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx

uv run main.py

