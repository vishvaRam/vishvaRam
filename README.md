<div align="center">

# 🌌 Vishva Ram
### Generative AI Engineer — LLM Quantization • High-Throughput Serving • Graph & Agentic RAG

[![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-Vishva007-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/Vishva007)
[![HF Collections](https://img.shields.io/badge/🤗_Model_Collections-FF9D00?style=for-the-badge&logoColor=white)](https://huggingface.co/Vishva007/collections)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-vishva123-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/u/vishva123)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vishva--r-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vishva-r)

> *"Optimization is not just about speed; it's about making advanced AI architecturally sustainable."*

</div>

---

## ⚡ Who I Am & What I Do

I am a **Generative AI Engineer** focused on compressing frontier Vision-Language and Large Language Models for production-grade inference and building graph-grounded agentic architectures. My work spans low-level model quantization (**W4A16**, **NVFP4**, **GPTQ**, **AWQ**), multi-GPU inference tuning (**vLLM**, **SGLang**), and stateful multi-agent RAG systems (**LangGraph**, **Qdrant**, **Neo4j**).

- **Model Compression & Serving:** Publishing production-ready quantized VLMs, OCR engines, and reasoning LLMs on [Hugging Face](https://huggingface.co/Vishva007) alongside reproducible CUDA/PyTorch RunPod environments on [Docker Hub](https://hub.docker.com/u/vishva123).
- **Upstream Open-Source:** Contributed the official quantization example directories for all of these model families directly to **Intel AutoRound**, alongside core features and fixes in **HKUDS LightRAG** and **vLLM**.
- **Agentic & Multimodal Systems:** Architecting self-healing Hybrid/Graph RAG pipelines and real-time vision-audio verification platforms (**YOLOv26**, **Whisper ASR**).

---

## 🤗 Hugging Face Model Hub (`Vishva007`)

Browse all quantized model families and checkpoints in my **[Hugging Face Collections](https://huggingface.co/Vishva007/collections)**. I authored and contributed the full upstream quantization example directories for **every model family listed below** into the official [`intel/auto-round`](https://github.com/intel/auto-round/tree/main/examples) repository.

### 🏆 Flagship Releases
- **[`Vishva007/gemma-4-E4B-it-W4A16-AutoRound-GPTQ`](https://huggingface.co/Vishva007/gemma-4-E4B-it-W4A16-AutoRound-GPTQ)** — **184,172** total downloads
- **[`Vishva007/Qwen3.8-27B-W4A16-AutoRound-GPTQ`](https://huggingface.co/Vishva007/Qwen3.8-27B-W4A16-AutoRound-GPTQ)** — **136,363** total downloads

### 📦 Quantized Model Suites (with Upstream `auto-round` Example Directories)
| Model Family | Variants & Formats | Primary Domain |
| :--- | :--- | :--- |
| **Gemma 4** (`12B-it`, `E4B-it`) | W4A16 (AutoRound, GPTQ, AWQ) | Multimodal Image-Text Understanding |
| **Qwen 3.8 & 3.8 Distill** (`27B`, `9B`, `4B`) | W4A16 (AutoRound, GPTQ, LLM-Compressor) | Multimodal Reasoning & Distilled VLMs |
| **Qwen 3.5 & Qwen3-VL** (`9B`, `8B`) | NVFP4, W4A16 (AutoRound, GPTQ, AWQ) | Blackwell NVFP4 & Vision-Language Serving |
| **Document OCR & Extraction** | NVFP4, W4A16 (AutoRound, GPTQ) | `dots.mocr`, `LightOnOCR-3` (`4B`/`0.8B`), `NuExtract3` |
| **Swift 1.5 Ornith-9B & MiMo V2.6** | NVFP4, W4A16 (AutoRound, GPTQ, LLM-Compressor) | Image-Text Understanding & Distilled 9B Models |
| **Decision & Edge VLMs** | W4A16 (AutoRound, GPTQ) | `vLLM-sr Decision 3.0`, `Clef`, `LiquidAI d1-3B`, `Muse-Glimmer-30B` |

---

## 🧪 Open-Source Contributions & Featured Engineering

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Upstream Open-Source
- **Intel `auto-round`:** Authored and contributed complete quantization example directories across **all 15 model families** on my Hub (Gemma 4, Qwen 3.8/3.5/VL, LightOnOCR-3, dots.mocr, NuExtract3, Swift 1.5 Ornith-9B, MiMo V2.6, vLLM-sr Decision 3.0, Clef, LiquidAI d1-3B, Muse-Glimmer-30B, and more), diagnosed W4A16 AWQ serialization bugs for Qwen3-VL ([Issue #1377](https://github.com/intel/auto-round/issues/1377)), and validated long-context (`seqlen=4096`) calibration dataset loaders.
- **HKUDS `LightRAG`:** Contributed official **Google Gemini API** integration and PostgreSQL multi-tenant workspace isolation ([PR #2538](https://github.com/HKUDS/LightRAG/pull/2538), [PR #2556](https://github.com/HKUDS/LightRAG/pull/2556), [PR #2615](https://github.com/HKUDS/LightRAG/pull/2615)).

</td>
<td width="50%" valign="top">

### 🚀 Featured Systems & Tooling
- **Qdrant Vector Space X-Ray:** Interactive 3D embedding space visualizer built with FastAPI, Three.js, and Plotly for inspecting high-dimensional Qdrant collections.
- **Agentic LightRAG Audit & Compliance Engines:** Multi-agent LangGraph loops backed by Qdrant (BM25 + Dense RRF) and Neo4j property graphs for long-form financial/regulatory analysis and self-healing retrieval.
- **AI-Driven vKYC Automation Platform:** End-to-end multimodal identity verification pipeline combining **YOLOv26**, **Whisper ASR**, and LLM cross-verification.

</td>
</tr>
</table>

---

## 🛠️ Core Stack

| Domain | Technologies |
| :--- | :--- |
| **Quantization & Inference** | **vLLM**, **AutoRound**, NVFP4, GPTQ, AWQ, LLM-Compressor, SGLang, llama.cpp |
| **Agentic & Graph RAG** | LangGraph, LangChain, LightRAG, Qdrant, Neo4j, BM25 + Semantic RRF, Ragas, Langfuse |
| **Multimodal & Fine-Tuning** | PyTorch, CUDA, QLoRA, Unsloth, PEFT, YOLOv26, Whisper ASR |
| **Cloud & Infrastructure** | Python, FastAPI, Docker, Podman, RunPod, AWS (S3, EC2, ECS, ECR) |

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=vishvaRam&theme=dark&show_icons=true&hide_border=true" alt="Vishva's GitHub Stats" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vishvaRam&theme=dark&hide_border=true" alt="Vishva's GitHub Streak" width="49%" />
  <br />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=vishvaRam&theme=dark&layout=compact&hide_border=true" alt="Top Languages" width="55%" />
</div>

---

<div align="center">

### 🌍 Connect
**[Hugging Face](https://huggingface.co/Vishva007)** • **[HF Collections](https://huggingface.co/Vishva007/collections)** • **[Docker Hub](https://hub.docker.com/u/vishva123)** • **[LinkedIn](https://linkedin.com/in/vishva-r)** • **[Instagram](https://instagram.com/justt_vishva)**

*Building the infrastructure that makes AI smarter, faster, and more accessible.*

</div>
