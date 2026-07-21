# Hey, I'm Arthur 👋

AI Engineer building production ML systems at Monaco Digital.

## What I work on
- 🤖 LLM-powered chatbots with RAG (Milvus, LangChain)
- 🎥 Video analysis with fine-tuned Vision-Language Models
- 🏗️ End-to-end ML pipelines: training → serving → monitoring
- 🐳 Containerized deployments on Azure

## Tech Stack
Python • PyTorch • Hugging Face • LangChain • Docker • Azure • FastAPI • Milvus

## Featured Projects

### [EquiTone](https://github.com/rodriguezarthur/EquiTone) — debiasing video datasets by skin tone
Rebalances the skin-tone distribution of a video dataset **without touching the motion**.
Per-identity segmentation with SAM 2, then an affine retonage in CIELAB anchored on the
Monk Skin Tone scale (ITA°, CIEDE2000) — so existing gesture annotations stay valid and
no re-labelling is needed. Ships a `scan → plan → run-plan` CLI and a provenance sidecar
per generated clip.

`Python` · `PyTorch` · `SAM 2` · `OpenCV` · `scikit-image`
