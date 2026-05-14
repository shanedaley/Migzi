# Migzi.ai — WebGPU-Powered 3D Document Platform

> ⚠️ **Migzi.ai requires a browser with WebGPU support enabled.**  
> For the best experience, use the latest version of **Chrome**, **Edge**, or another Chromium-based browser with WebGPU support.

![Migzi.ai Screenshot](https://raw.githubusercontent.com/shanedaley/Migzi/refs/heads/main/Screenshot%202026-05-14%20at%2009.39.47.png)

Migzi.ai is a next-generation browser-based 3D platform that allows users to import **PDFs and PowerPoints** into immersive environments.

Built with **WebGPU**, **Three.js**, and a custom GPU rendering pipeline designed for modern graphics hardware.

---

# 🚀 Features

| Feature | Description |
|---|---|
| 🖥️ **WebGPU Rendering Pipeline** | High-performance rendering using compute shaders, GPU buffers, and custom rendering pipelines. |
| 📄 **3D Document Viewer** | Import PDFs and PowerPoints directly into immersive 3D scenes. |
| ⚡ **GPU-Accelerated Performance** | Optimised for modern GPUs and large multi-page environments. |
| 🧩 **React + Three.js Frontend** | Modular component-driven architecture for UI and scene management. |
| 🗂️ **Node.js Backend** | Handles file processing, conversion, asset delivery, and caching. |
| 🌐 **Immersive Navigation** | Explore documents spatially inside interactive 3D environments. |

---

# 🧱 Architecture Overview

Migzi.ai is split into two main layers:

## Frontend (React + Three.js + WebGPU)

- 🎮 Scene management
- ⚡ GPU pipelines
- 🧠 Interaction systems
- 🖼️ Document rendering
- 🎨 UI/UX systems

## Backend (Node.js + SQL)

- 📤 File upload & processing
- 📄 PDF/PPT conversion
- 🗄️ Asset caching
- 👤 User/session management

---

# 📂 Project Structure

```bash
/client      → React + Three.js frontend
/server      → Node.js backend
/assets      → Processed document assets
/shaders     → WebGPU shader pipelines
/components  → Reusable UI & scene components
