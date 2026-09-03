<h1 align="center">Samuel Carvalho</h1>

<p align="center">
  <b>AI Engineer — RAG · Fine-tuning · LLMOps</b><br>
  <sub>Private, production GenAI systems, built end to end and measured before they ship.</sub>
</p>

<p align="center">
  <a href="https://samuel-carvalho.com"><img src="https://img.shields.io/badge/Portfolio-samuel--carvalho.com-0F3D5C?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/samusafe/"><img src="https://img.shields.io/badge/LinkedIn-samusafe-0F3D5C?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:samucarvalhocp@gmail.com"><img src="https://img.shields.io/badge/Email-samucarvalhocp%40gmail.com-0F3D5C?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## About

Final-year Computer Engineering student in Porto, building private, on-prem AI systems from the backend and queues to the RAG pipeline, the fine-tuned model and the desktop UI. I don't ship an AI change without a number behind it: every retrieval or model change goes through [rag-eval-harness](https://github.com/samusafe/rag-eval-harness) before it lands.

At [Fashable](https://samuel-carvalho.com) I built the backend and Azure infrastructure behind multimodal product search, demoed the MVP at **NRF 2024 (New York)** and saw it ship on the **Microsoft Marketplace** as a Teams Copilot app.

## Featured projects

| Project | What it is | What it shows |
|---|---|---|
| [**rag-eval-harness**](https://github.com/samusafe/rag-eval-harness) | Regression gates for RAG pipelines: hit rate, MRR, keyword recall, refusal and citation checks, p95 latency, threshold gates and per-question diffs between runs. No LLM-as-judge. | Evaluation discipline. The same loop LocalVault runs internally. |
| [**qlora-8gb-pipeline**](https://github.com/samusafe/qlora-8gb-pipeline) | JSONL dataset → 4-bit QLoRA adapter (Unsloth + TRL, Qwen 2.5 3B) → GGUF for Ollama, on a single RTX 4060. Digest-pinned Docker image and a provenance manifest per run. | Reproducible fine-tuning under a hard memory budget. |
| [**swiss-legal-rag**](https://github.com/samusafe/swiss-legal-rag) · alpha | Local, trilingual RAG over Swiss federal law (Fedlex, DE/FR/IT): hybrid pgvector + full-text search with Reciprocal Rank Fusion, cross-encoder reranking, article-level citations, 33-question gold set. Offline Tauri desktop app. | Multilingual retrieval with citations you can check. |
| [**YOLOv8**](https://github.com/samusafe/YOLOv8) | Retail shelf monitoring on SKU-110K and Shelves: 0.900 mAP@0.5 with Nano at ~3.2 ms per image on an RTX 4060. | More labelled data beat a 3× larger backbone. |
| **LocalVault** · closed-source | On-prem AI platform: local RAG (pgvector, cross-encoder reranking, semantic cache), QLoRA fine-tuning on an 8 GB GPU, MLflow evals and Langfuse tracing. NestJS + BullMQ backend, Tauri/React desktop app. | The system the three tools above were built for. [Case study →](https://samuel-carvalho.com/localvault) |

More case studies, including maiai and nexus-doc-ai, on [samuel-carvalho.com/projects](https://samuel-carvalho.com/projects).

## Stack

<table align="center">
  <tr>
    <td align="center" width="33%">
      <b>AI / LLM</b><br><br>
      <img src="https://skillicons.dev/icons?i=python,pytorch,fastapi" /><br>
      <sub>LangChain • pgvector • Ollama<br>QLoRA / Unsloth • Langfuse • MLflow</sub>
    </td>
    <td align="center" width="33%">
      <b>Backend & Data</b><br><br>
      <img src="https://skillicons.dev/icons?i=nestjs,nodejs,ts,postgres,redis" /><br>
      <sub>NestJS • Prisma • BullMQ<br>PostgreSQL • Redis</sub>
    </td>
    <td align="center" width="33%">
      <b>Frontend & Infra</b><br><br>
      <img src="https://skillicons.dev/icons?i=react,tauri,docker,azure,linux" /><br>
      <sub>React • Tauri • Tailwind<br>Docker • MinIO • Azure</sub>
    </td>
  </tr>
</table>

<p align="center"><sub>Also comfortable with Java (Spring Boot), Go and MongoDB.</sub></p>
