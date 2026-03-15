# Multi-Agent AI Digest

A containerized pipeline of AI agents that ingest local files, summarize them using GPT-4o, prioritize insights, and format a daily markdown digest.

## 📁 Structure
- **Ingestor**: Reads local `.txt` files from `/data/input`.
- **Summarizer**: Processes text through OpenAI.
- **Prioritizer**: Scores insights based on urgency.
- **Formatter**: Generates a final `daily_digest.md`.

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone https://github.com
   cd multi-agent-digest
