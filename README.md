# Local LLM Runtime Using Rust

A semester project focused on the **design and implementation of a local, offline Large Language Model (LLM) runtime** using the Rust programming language and a native inference library.

This project demonstrates how modern AI models can be executed locally without relying on cloud services, emphasizing **privacy, performance, and system-level design**.

---

## 📌 Project Overview

Most Large Language Models today are accessed through cloud-based platforms, which introduces challenges related to data privacy, latency, cost, and internet dependency.  
This project aims to address these limitations by building a **local LLM execution system** that runs entirely on consumer hardware.

The system integrates a native inference engine with a Rust-based asynchronous server to provide text generation through a simple REST API.

---

## 🎯 Objectives

- Design a local LLM runtime architecture
- Execute LLM inference fully offline
- Integrate a native inference engine with Rust
- Expose REST-based APIs for text generation
- Support streaming responses
- Ensure memory safety and performance efficiency

---

## 🧱 System Architecture (High Level)

- **API Server** – Handles client requests and responses
- **Model Manager** – Loads and manages the LLM lifecycle
- **Inference Engine** – Native model execution via llama.cpp
- **Streaming Module** – Streams generated tokens incrementally

---

## 🛠 Technology Stack

| Layer | Technology |
|------|-----------|
| Language | Rust |
| Async Runtime | Tokio |
| API Framework | Axum |
| Inference Engine | llama.cpp |
| Model Format | GGUF |
| CLI Tooling | Clap |
| Serialization | Serde |

---

## 📂 Project Status

🔹 **Current Phase:** Planning & Design  
🔹 **Implementation Starts:** Beginning of semester  
🔹 **Target:** Academic semester project submission  

---

## 🚧 Scope Limitations

- Inference-only execution (no model training)
- CPU-based execution
- No web-based UI
- No multi-user authentication
- Single-model support (initial version)

---

## 📅 Planned Milestones

- Architecture & design documentation
- Native inference integration
- REST API implementation
- Streaming response support
- Testing & performance evaluation
- Final report & presentation

---

## 📖 Documentation

- Project Report: `/report/`
- Design Diagrams: `/docs/`
- Source Code: `/src/`

---

## 📜 License

This project is developed as part of an academic semester project and is intended for educational purposes.
