# HR AI Evaluation Lab

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge">
  <img src="https://img.shields.io/badge/Qwen2.5--14B-615CED?style=for-the-badge">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white">
</p>

### 🌐 [View the project website](https://roaa-thg.github.io/AIDC-RCP-HR/reports/HR_AI.html)

---

An automated system that reads resumes in **Arabic and English** and turns them into structured candidate profiles. When HR adds a job description, it scores every resume against it and shows the matched and missing skills.

Built with FastAPI and **Qwen2.5-14B**, self-hosted on vLLM.

## What We Learned

- Self-hosting and serving an LLM on a single GPU with vLLM
- Benchmarking extraction quality (F1, hallucination) across Arabic and English
- Measuring serving performance: time to first token, throughput, latency
- Comparing API-based vs self-hosted models on quality and cost
- Getting reliable structured JSON output from an LLM

## Team 8

- Balsam Alahmary
- Rana Alshaikh
- Roaa Althagafi
- Munirah Alfarawi

---

AIDC Bootcamp Capstone · Built for Beamdata.ai
