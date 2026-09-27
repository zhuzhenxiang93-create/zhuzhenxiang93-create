# Zhenxiang Zhu

**AI Product Builder · LLM Agents · RAG · Multimodal AI · AI Evaluation**

Master of Artificial Intelligence at the **University of Auckland**, with a Computer Science background.  
I enjoy turning AI capabilities into **clear user workflows, reliable system behavior, measurable evaluation, and iterative product improvements**.

## What I focus on

```text
User Problem
    ↓
Product Workflow
    ↓
AI Capability & System Design
    ↓
Evaluation
    ↓
Bad Case Analysis
    ↓
Iteration
```

My current interests include **LLM Agents, RAG, multimodal AI, tool use, grounded generation, human-in-the-loop workflows, and AI product evaluation**.

## Featured Projects

| Project | What it solves | Product / AI highlights |
|---|---|---|
| **[ResolveFlow](https://github.com/zhuzhenxiang93-create/ResolveFlow)** | Customer-service workflows for membership, billing, logistics and technical issues | Agent routing, controlled business workflows, tool use, RAG, memory, evaluation |
| **[VideoRAG](https://github.com/zhuzhenxiang93-create/VideoRAG)** | Helps users ask questions about tutorial videos and jump directly to supporting evidence | Multimodal retrieval, timestamped evidence, RRF + reranking, grounded answers, evaluation |
| **[LegalMind-RAG](https://github.com/zhuzhenxiang93-create/RAG)** | Turns anonymized case facts into traceable evidence and reviewable structured analysis | Qwen3-4B LoRA, charge-aware hybrid retrieval, RRF, reranker, evidence validation, controlled generation |

### ResolveFlow

A customer-service Agent system for paid-membership scenarios. It combines conversational AI with deterministic business workflows so that information requests can be handled flexibly while operations such as refunds or subscription changes remain controlled and traceable.

**Key ideas:** Agent routing · Tool use · Controlled workflow · RAG · Memory · Evaluation

### VideoRAG

A multimodal video question-answering system designed around a simple user problem: finding a specific step in a tutorial video without repeatedly dragging the progress bar. It returns an answer together with supporting video evidence and timestamps.

**Key ideas:** Whisper · Qwen2.5-VL · Qwen3-Embedding · Chinese-CLIP · RRF · Reranker · Grounded answer

### LegalMind-RAG

An evidence-grounded criminal-case analysis research prototype that connects multi-label charge classification, charge-aware case retrieval, statute evidence, structured generation and validation into a reviewable workflow.

**Key ideas:** Qwen3-4B LoRA · BM25 + Dense retrieval · RRF · Neural reranking · Evidence IDs · Validation

## Product mindset

When building AI applications, I care about more than whether a model can produce an answer. I focus on questions such as:

- What user problem are we solving?
- Which decisions should be made by the model, and which should remain deterministic?
- What evidence should the user be able to inspect?
- How should failure, uncertainty and abstention be handled?
- Which offline and end-to-end metrics actually reflect the user experience?
- How can logs, tool traces and bad cases drive the next iteration?

## Tech

**AI:** LLM · VLM · RAG · Agent Workflow · Tool Use · Reranker · Embedding · Grounded Generation · Human-in-the-loop  
**Engineering:** Python · FastAPI · PyTorch · SQL/MySQL · Redis · ChromaDB · FAISS  
**Product:** User-flow design · AI workflow design · Evaluation design · Bad-case analysis · Axure

---

*Building AI systems that are useful, inspectable, and measurable.*
