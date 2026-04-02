[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0d0d0d,100:1a1a1a&height=160&section=header&text=YamiLogic&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=LLM%20Research%20%7C%20RAG%20Architecture%20%7C%20Reinforcement%20Learning%20Systems&descAlignY=58&descSize=14&descColor=888888)](https://github.com/YamiLogic)

## ∴ About Me:

🧠 Hi, I'm **YamiLogic** — researching and building production-grade LLM systems from the ground up.<br><br>
🔬 Deep in: **RAG Pipelines · RL-Optimized Retrieval · PPO Agents · MCP Architecture** — not demos, real systems.<br><br>
⚙️ Working with: **HuggingFace · Groq · Cohere · LangChain · LangGraph · pgvector · Ollama** — full stack from embedding to deployment.<br><br>
🚀 Currently building:<br>
&nbsp;&nbsp;&nbsp;&nbsp;* RL-loop RAG Microservice — PPO agent selecting model + retrieval strategy in real-time<br>
&nbsp;&nbsp;&nbsp;&nbsp;* MCP Tool Server wrapping public APIs — FastAPI · Redis · Kafka · PostgreSQL<br>
&nbsp;&nbsp;&nbsp;&nbsp;* Fine-tuning pipelines on HuggingFace with custom reward modeling<br><br>
⚡ Philosophy: `understand the loss function → break the system → rebuild it better`


# 📦 3D Contribution Graph:

![3D Contrib](https://raw.githubusercontent.com/YamiLogic/YamiLogic/output/profile-south-season-animate.svg)


## 🌐 Socials:
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/YamiLogic)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/YamiLogic)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/your-linkedin)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:your@email.com)

# 💻 Tech Stack:

**🤖 LLM / GenAI**<br>
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2C5F2E?style=for-the-badge&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-FF4B00?style=for-the-badge&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-6B4FBB?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**🗄️ Vector & Memory**<br>
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF5A5F?style=for-the-badge&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)

**🎯 Reinforcement Learning**<br>
![PPO](https://img.shields.io/badge/PPO_Agent-222222?style=for-the-badge&logoColor=white)
![StableBaselines3](https://img.shields.io/badge/Stable--Baselines3-333333?style=for-the-badge&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A7?style=for-the-badge&logoColor=white)
![RLHF](https://img.shields.io/badge/RLHF-8B0000?style=for-the-badge&logoColor=white)

**🧠 ML / Deep Learning**<br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

**⚙️ Backend & Infra**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

# 🔬 Active Research Build:

```
RL-loop-RAG-Microservice
├── Backend-FastAPI        :8000  — query orchestration + reward logging
├── RL-Agent-Service       :8001  — PPO agent driving model & retrieval selection
├── MCP-Tools-Server       :8002  — external tool calls + API wrappers
├── Neon-PostgreSQL+pgvec         — long-term memory + vector store
└── Streamlit-Frontend     :8501  — user feedback → reward signal

State  : [query_embedding, retrieved_chunks, model_id, latency, prev_reward]
Action : [model_selection, retrieval_strategy, chunk_count, rerank_flag]
Reward : ROUGE-L + semantic_similarity - latency_penalty + user_feedback_score
```

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=YamiLogic&theme=dark&hide_border=false&include_all_commits=true&count_private=true&hide=issues&bg_color=0d1117&title_color=ffffff&text_color=888888&icon_color=58a6ff&custom_title=Commits%20%26%20Activity)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=YamiLogic&theme=dark&hide_border=false&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=888888)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=YamiLogic&theme=dark&hide_border=false&bg_color=0d1117&title_color=ffffff&text_color=888888&layout=compact&custom_title=Languages)


# 🐍 Contribution Snake:

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YamiLogic/YamiLogic/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YamiLogic/YamiLogic/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/YamiLogic/YamiLogic/output/github-contribution-grid-snake.svg" />
</picture>

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=YamiLogic&icon=0&color=0)](https://visitcount.itsvg.in)

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a1a,50:0d0d0d,100:000000&height=100&section=footer)](https://github.com/YamiLogic)
