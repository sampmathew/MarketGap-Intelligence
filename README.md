# MarketGap Intelligence Pro 🚀

> **An AI-Driven B2B SaaS Platform for Automated Product Sentiment & Revenue Analysis**

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Build_Tool-Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![AI/RAG](https://img.shields.io/badge/AI-Gemini_2.5_%7C_ChromaDB-FF6F00?logo=google&logoColor=white)

---

## 📌 Overview

**MarketGap Intelligence Pro** bridges the gap between raw data science and executive business strategy. E-commerce brands receive thousands of unstructured text reviews daily across various platforms. Standard analytics are purely descriptive—meaning companies often only realize a product has a critical flaw *after* revenue drops.

This platform automates data ingestion, converts unstructured customer feedback into interactive visual dashboards, calculates the estimated **Revenue at Risk** from product defects, and features an AI-powered **Strategic Copilot** that allows product managers to directly chat with customer complaint datasets using Retrieval-Augmented Generation (RAG).

---

## ✨ Key Features

* **🔄 Universal Schema Mapper:** Dynamically reads and maps unstructured CSV/Excel review datasets without predefined headers using LLMs.
* **💸 Financial Impact Calculator:** Directly quantifies negative sentiment and specific product defects into estimated lost sales dollars (Revenue at Risk).
* **📊 Aspect-Based Radar Charts:** Breaks down customer sentiment granularly into specific categories: *Quality*, *Price*, and *Customer Service*.
* **🤖 RAG Strategic Copilot:** Powered by Google Gemini and ChromaDB, allowing users to query their dataset conversationally to receive data-backed remediation advice.
* **📝 One-Click Executive Brief:** Automatically drafts a downloadable, board-ready Markdown summary highlighting core product flaws and strategic fixes.
* **🎨 Modern Dark-Mode UI:** Built with Tailwind CSS for a RAWGraphs-inspired aesthetic that reduces eye strain and emphasizes visual data contrast.

---

## 🛠️ Tech Stack

### **Frontend (Vite / React / Tailwind CSS)**
* **Framework:** React (Single Page Application)
* **Build Tool:** Vite for lightning-fast Hot Module Replacement (HMR) and optimized production builds.
* **Styling:** Tailwind CSS & PostCSS for responsive, custom dark-mode UI components.
* **Visualization:** Plotly / Plotly.js for rendering interactive financial and sentiment distributions.

### **Backend (Python / FastAPI / AI Core)**
* **API Routing:** FastAPI for high-performance, asynchronous endpoints and seamless client-server communication.
* **Data Wrangling:** Pandas for filtering, cleaning, and aggregating positive/negative review subsets.
* **AI & LLM:** Google Gemini 2.5 Flash API for automated schema mapping, insights generation, and executive reporting.
* **Vector Database:** ChromaDB for local embedding storage and similarity search powering the RAG Copilot.

---

## 📂 Repository Structure

```text
├── __pycache__/             # Python bytecode cache
├── index.html               # Main HTML entry point for Vite/React SPA
├── main.py                  # FastAPI server entry point, API routing & AI logic
├── package.json             # Node.js dependencies and scripts for frontend UI
├── package-lock.json        # Lockfile for frontend dependency versions
├── postcss.config.js        # PostCSS configuration for Tailwind CSS integration
├── tailwind.config.js       # Tailwind CSS styling, theme, and responsive breakpoints
└── vite.config.js           # Vite configuration for development server and bundling
