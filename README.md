# Awesome Artificial Intelligence

Uma colecao curada de **recursos indispensaveis e ativamente mantidos** para construir e colocar sistemas de IA em producao.

Foco: **engenharia de IA** (RAG, agents, evals, guardrails, deploy), alem dos melhores livros, guias, artigos e um conjunto de ferramentas *cuidadosamente selecionado*.

![](https://media.giphy.com/media/jeAQYN9FfROX6/giphy.gif)

---

## 🏛 Recursos Essenciais

_Os fundamentos - estes recursos continuarao valiosos daqui a cinco anos, mesmo que as ferramentas de hoje desaparecam._

### 📚 Livros
**Modernos e Praticos**
- [Designing Machine Learning Systems](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) — Pipelines de ML escalaveis e de facil manutencao (Chip Huyen).
- [Generative Deep Learning (2nd Edition)](https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/) — GANs, VAEs, diffusion models (David Foster).
- [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) — Desenvolvimento de produtos de IA de ponta a ponta (Chip Huyen).
- [100 Page Language Models Book](https://www.thelmbook.com/) — Este livro guia voce pela evolucao dos language models, comecando pelos fundamentos de machine learning.

**Fundamentais**
- [Artificial Intelligence: A Modern Approach](https://aima.cs.berkeley.edu/) — Teoria de IA abrangente (Russell & Norvig).
- [Deep Learning](https://www.deeplearningbook.org/) — Redes neurais e arquiteturas (Goodfellow, Bengio, Courville).
- [Reinforcement Learning: An Introduction (2nd Edition)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf) — Fundamentos de RL (Sutton & Barto).

---

### 🏗 Engenharia de IA
_Frameworks e padroes de design para construir sistemas de IA robustos e prontos para producao._
_Nota pessoal: voce nao precisa de um monte de frameworks - comece com chamadas simples para LLM e evolua a partir disso._

#### 📖 Guias e Playbooks
- **[Building Effective Agents (Anthropic)](https://www.anthropic.com/engineering/building-effective-agents)** — ⭐ Padroes, armadilhas e tradeoffs para projetar agentes de IA.
- [OpenAI Agents Guide](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf) — Guia pratico para construir agentes
- [Google AI Agents Paper](https://www.kaggle.com/whitepaper-agents) - Guia pratico do Google para construir agentes de IA
- [Google Agents Companion Paper](https://www.kaggle.com/whitepaper-agent-companion) - Guia complementar do Google
- [OpenAI Cookbook](https://cookbook.openai.com/) — Codigo de exemplo, receitas e boas praticas para trabalhar com as APIs da OpenAI.
- [LLM Engineer Handbook](https://github.com/SylphAI-Inc/LLM-engineer-handbook) — Uma mina de ouro de links uteis para engenheiros de IA

#### 🤖 Frameworks
- [PocketFlow](https://the-pocket.github.io/PocketFlow/) — Framework extremamente minimalista para agentes de IA em apenas 100 linhas de codigo. Excelente para aprender.
- [Google ADK](https://google.github.io/adk-docs/) — Agent Development Kit do Google (Python, Java). Excelente experiencia de desenvolvimento local + A2A + MCP.
- [Pydantic-AI](https://ai.pydantic.dev/) — Framework tipado e estruturado de orquestracao de LLM, construido sobre modelos Pydantic para saidas seguras e previsiveis.
- [LangGraph](https://www.langchain.com/langgraph) — Construa fluxos multi-agent com grafos com estado sobre o LangChain.
- [CrewAI](https://www.crewai.com/) — Orquestracao de agents com tarefas estruturadas e controles human-in-the-loop.
- [AutoGen](https://microsoft.github.io/autogen/) — Framework da Microsoft para conversa e colaboracao multi-agent.

#### 📦 Retrieval-Augmented Generation (RAG)
- [LlamaIndex](https://www.llamaindex.ai/) — Framework de dados para ingestao, indexacao e consulta de dados privados com LLMs.
- [Haystack](https://haystack.deepset.ai/) — Framework open-source de busca/RAG com pipelines modulares.
- [Docling](https://github.com/docling-project/docling) — Excelente biblioteca para ingerir qualquer tipo de documento para RAG ⭐

#### Avaliacoes

- [OpenAI Evals](https://github.com/openai/evals) — Framework da OpenAI para escrever avaliacoes

---

### 📄 Artigos Fundamentais
_Pesquisas que moldaram a IA moderna - vale a pena ler para entender o "por que" por tras das arquiteturas atuais._
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Arquitetura Transformer.
- [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361) — Escalabilidade de modelo/dados/compute.
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) — Capacidades do GPT-3.
- [Constitutional AI](https://arxiv.org/abs/2212.08073) — Alinhamento de modelos mais seguro.

---

## 🎓 Cursos
_Aprenda com os melhores - conteudo estruturado para todos os niveis._

**Iniciante**
- [Google Generative AI Learning Path](https://www.cloudskillsboost.google/paths/118)
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Fast.ai — Practical Deep Learning](https://course.fast.ai/)

**Intermediario / Avancado**
- [Stanford CS324: Large Language Models](https://stanford-cs324.github.io/winter2022/)
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/)
- [MIT 6.S191: Intro to Deep Learning](https://introtodeeplearning.com/)

**Focados**
- [DeepLearning.AI Short Courses](https://learn.deeplearning.ai/)
- [Google Deepmind| Introduction to Reinforcement Learning](https://www.youtube.com/playlist?list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ)
- [Karpathy’s LLM Zero-to-Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
- [Neural Nets - Zero-to-Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

---

## 📰 Newsletters
_Acompanhe as novidades de IA sem se perder no ruido._
- [The Rundown AI](https://www.therundown.ai/)
- [AlphaSignal](https://alphasignal.ai/)
- [Superhuman AI](https://www.superhuman.ai/)
- [AI Engineer](https://newsletter.owainlewis.com)

## ⚡ Ferramentas

Ferramentas para construir e colocar aplicacoes de IA em producao.

### 💬 Modelos
- [ChatGPT](https://openai.com/chatgpt/overview/) — Melhor para programacao geral e raciocinio.
- [Claude](https://www.anthropic.com/claude) — Melhor para analise com contexto longo e pensamento estruturado.
- [Gemini](https://gemini.google.com/) — Melhor para integracao com o ecossistema Google.
- [Perplexity](https://www.perplexity.ai/) — Melhor para pesquisa rapida com citacoes em tempo real.
- [Cohere](https://cohere.com/) — Melhor para LLMs corporativos com APIs fortes de retrieval-augmented generation.
- [Mistral](https://mistral.ai/) — Melhor para modelos open-weight leves e de alto desempenho.
- [Qwen](https://qwenlm.github.io/) — Melhor para aplicacoes multilingues e focadas primeiro em chines.
- [DeepSeek](https://deepseek.com/) — Melhor para modelos grandes eficientes, com custo otimizado e raciocinio competitivo.

### 👨‍💻 Ferramentas de Codigo e Desenvolvimento
- [Claude Code](https://www.anthropic.com/claude) — Extensoes para IDE com edicoes de codigo de contexto longo.
- [GitHub Copilot](https://github.com/features/copilot) — Autocompletar codigo, chat e refatoracoes dentro da IDE.
- [Cursor](https://cursor.sh/) — IDE com suporte a LLM para edicoes em varios arquivos e chat com conhecimento da codebase.

### 🎨 Ferramentas de IA para Multimidia

#### 🖼 Imagem
- [ChatGPT-4o Image Generation](https://openai.com/chatgpt) — Criacao de imagem integrada com controle de estilo.
- [Midjourney](https://www.midjourney.com/) — Imagens e video artisticos e fotorrealistas.
- [Adobe Firefly](https://www.adobe.com/sensei/generative-ai/firefly.html) — Integrado ao Creative Cloud.
- [Ideogram](https://ideogram.ai/) — Texto preciso e legivel em imagens geradas.
- [Flux](https://blackforestlabs.ai/) — Imagens em alta resolucao com prompts editaveis.

#### 🎥 Video
- [Kling](https://klingai.com/) — Geracao de video cinematografica e realista.
- [Google Veo 3](https://deepmind.google/technologies/veo/) — Video de alta qualidade com audio sincronizado.
- [Runway](https://runwayml.com/) — Edicao e geracao de video.

#### 🎙 Audio
- [ElevenLabs](https://elevenlabs.io/) — Text-to-speech de alta qualidade.
- [Suno](https://suno.ai/) — Musica com IA a partir de prompts em texto.
- [Aiva](https://www.aiva.ai/) — Composicao musical para midia.

---
