# AI Agents Codebook

Comprehensive collection of AI agent patterns, frameworks, and code examples organized by topic.

## 📚 Course Structure

This codebook covers AI agent development across 21 chapters plus appendices:

| Chapter | Topic | Description |
|---------|-------|-------------|
| 1 | Prompt Chaining | Sequential prompt patterns |
| 2 | Routing | Intelligent request routing |
| 3 | Parallelization | Concurrent task execution |
| 4 | Reflection | Self-improvement patterns |
| 5 | Tool Use | Function calling & external tools |
| 6 | Planning | Goal-oriented agents |
| 7 | Multi-Agent Collaboration | Agent-to-agent communication |
| 8 | Memory Management | State persistence patterns |
| 9 | Adaptation | Dynamic agent behavior |
| 10 | Model Context Protocol (MCP) | Standardized agent interfaces |
| 11 | Goal Setting & Monitoring | Objective tracking |
| 12 | Exception Handling | Error recovery patterns |
| 13 | Human-in-the-Loop | Interactive agents |
| 14 | Knowledge Retrieval | RAG implementations |
| 15 | Inter-Agent Communication | A2A protocols |
| 16 | Resource-Aware Optimization | Efficiency patterns |
| 17 | Reasoning Techniques | CoT & self-correction |
| 18 | Guardrails & Safety | Input/output validation |
| 19 | Evaluation & Monitoring | Performance metrics |
| 20 | Prioritization | Task scheduling |
| 21 | Exploration & Discovery | Agent experimentation |

## 📁 Project Structure

```
ai-agent-codebook/
├── notebooks/                    # Original Jupyter notebooks (56 files)
│   ├── Chapter 1_ Prompt Chaining.ipynb
│   ├── Chapter 2_ Routing.ipynb
│   └── ...
├── src/                          # Converted Python code (56 files)
│   ├── chapter1_prompt_chaining/
│   ├── chapter2_routing/
│   ├── chapter3_parallelization/
│   └── ...
├── tests/                        # Unit tests (to be added)
├── docs/                         # Additional documentation
├── requirements.txt              # Python dependencies
└── README.md                     # This file
```

## 🚀 Quick Start

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Examples

**From Jupyter Notebooks:**
```bash
jupyter notebook notebooks/
```

**From Python Files:**
```bash
# Example: Run Chapter 1 code
python src/chapter1_prompt_chaining/Chapter\ 1_\ Prompt\ Chaining\ \(Code\ Example\).py
```

## 🛠️ Frameworks Covered

| Framework | Usage |
|-----------|-------|
| LangChain | Core agent orchestration |
| LangGraph | Graph-based workflows |
| CrewAI | Multi-agent systems |
| Google ADK | Google's agent development kit |
| OpenAI | GPT-based agents |
| Weaviate | Vector database |
| Pydantic | Data validation |

## 📦 Dependencies

- **AI/ML:** langchain, langgraph, openai, google-generativeai
- **Agent Frameworks:** crewai, google-adk, openevolve
- **Data:** weaviate, pydantic
- **Utilities:** python-dotenv, requests, nest_asyncio

See `requirements.txt` for complete list with versions.

## 🔄 Conversion Scripts

- `extract_deps_and_convert.py` - Extract dependencies and convert notebooks
- `convert_to_py.py` - Organized chapter-by-chapter conversion

## 📝 Notes

- Jupyter notebooks are kept in `notebooks/` for interactive use
- Python files in `src/` are production-ready versions
- Code cells only (markdown excluded in .py files)
- Each .py file includes header with source notebook name

## 🤝 Contributing

Feel free to add tests, improve code organization, or add new patterns!

## 📄 License

Educational use - check individual notebook licensing.
