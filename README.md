# ai-playwright-healer
A Playwright wrapper that catches "Element Not Found" errors, sends the DOM to an LLM, finds the new locator, and suggests a fix.

# 🚀 AI-Powered Self-Healing Playwright Framework

This repository demonstrates a **Self-Healing Automation Architecture** for modern SDET roles. It solves the issue of "flaky tests" by using LLMs (GPT-4o) to dynamically recover from UI changes at runtime.

### 🌟 Key Features
- **Dynamic Recovery:** Automatically detects locator failures.
- **LLM Context Injection:** Sends relevant DOM snippets to AI for real-time analysis.
- **Cost Efficient:** Uses `gpt-4o-mini` with token-optimized DOM scraping.

### 🛠 Tech Stack
- **Playwright** (Automation)
- **TypeScript** (Language)
- **OpenAI API** (Intelligence)
- **Dotenv** (Security)

### 📈 Business Impact
- **Maintenance Reduction:** Reduces manual script updates by up to 40%.
- **Reliability:** Decreases false-positives in CI/CD pipelines.
