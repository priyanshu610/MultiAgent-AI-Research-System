# MultiAgent-AI-Research-System
🔬 Multi-agent AI system that autonomously searches, scrapes, writes &amp; critiques research reports using LangChain + Mistral AI + Streamlit

# 🔬 ResearchMind — Multi-Agent AI Research System

> Four specialized AI agents that collaborate to deliver a polished research report on any topic — automatically.

---

## 🧠 How It Works

ResearchMind runs a 4-step autonomous pipeline:

| Agent | Role |
|-------|------|
| 🔍 **Search Agent** | Gathers recent web information on the topic |
| 📄 **Reader Agent** | Scrapes top URLs for deeper content |
| ✍️ **Writer Chain** | Drafts a full, structured research report |
| 🧐 **Critic Chain** | Reviews and scores the report for quality |

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/multiagent-research-system.git
cd multiagent-research-system

# 2. Create virtual environment
pyenv local 3.10.14
python -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your API keys
cp .env.example .env
# Edit .env with your keys

# 5. Run the app
streamlit run app.py
```

---

## 🔑 Environment Variables

Create a `.env` file in the root:

```env
MISTRAL_API_KEY=your_mistral_key_here
TAVILY_API_KEY=your_tavily_key_here
```

---

## 🛠️ Tech Stack

- **[LangChain](https://langchain.com)** — Agent orchestration
- **[Mistral AI](https://mistral.ai)** — LLM backbone
- **[Streamlit](https://streamlit.io)** — Frontend UI
- **Tavily** — Web search tool

---

## 📁 Project Structure

```
├── app.py           # Streamlit UI
├── agents.py        # Agent & chain definitions
├── pipeline.py      # Pipeline logic
├── tools.py         # Web search & scraper tools
├── requirements.txt
└── .env
```
