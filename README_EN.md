# Universal-AI-Tester

English | [中文版](./README.md)

A powerful yet lightweight AI API testing tool contained within a single HTML file. No backend required—runs directly in your browser. Designed for developers to debug and interact with various Large Language Models (LLMs) and multi-modal APIs.

## ✨ Key Features
- **Multi-Modal Support**:
  - 💬 **Chat**: Streaming response, typewriter effect control, Markdown rendering, and vision input.
  - 🎨 **Image**: Support for DALL-E style image generation with history management.
  - 🎬 **Video**: Video generation task submission, polling, and preview.
- **Highly Flexible**:
  - Compatible with OpenAI, DeepSeek, Claude, Gemini, and other providers using standard API protocols.
  - Customizable parameters: Temperature, Top P, Max Tokens, etc.
- **Developer Utilities**:
  - **Token & Cost Calc**: Real-time token counting and cost estimation based on pricing.
  - **Local Privacy**: All configurations and histories are stored locally in the browser.
  - **Exporting**: Export chat history and generation logs to text files.

## 🚀 Quick Start
1. Download `index.html`.
2. Open it in any modern web browser.
3. Enter your `API Key` and `Base URL` in the sidebar to start testing.

## 📸 Preview
![Preview](img/demo.png)

## 🛠 Tech Stack
- HTML5 / CSS3 (macOS-inspired UI)
- Vanilla JavaScript (Fetch API)
- Marked.js (Markdown parsing)

## 📄 License
MIT License