# HomeWise 🏡

> **Interactive 3D Home Renovation & Building By-Law Explorer**  
> Helping homeowners navigate Malaysian renovation laws, PBT approvals, and township regulations with ease.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Three.js](https://img.shields.io/badge/Three.js-r128-black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v3.4-38B2AC)

---

## 📖 Overview

**HomeWise** is an interactive web application designed for homeowners, renovators, and township communities. It demystifies statutory building regulations—specifically the **Street, Drainage and Building Act 1974 (Act 133)**—and township renovation guidelines through an intuitive, color-coded 3D model and floorplan explorer.

Before hacking a wall or extending a porch, homeowners can visualize their house in 3D, inspect compliance levels, generate custom document checklists, and ask questions through the built-in legal assistant.

---

## ✨ Key Features

- **🎮 3D & Isometric Visual Explorer**:
  - Interactive 3D visualization powered by [Three.js](https://threejs.org/).
  - Multiple camera angles and elevations (Front, Ground Floor, First Floor, Rear Extension).
  - SVG overlay zones mapped directly onto house blueprints.

- **🚦 Color-Coded Compliance Legend**:
  - 🟢 **Allowed (Green)**: Standard non-structural cosmetic works that generally don't require permits.
  - 🟡 **Verify (Yellow)**: Requires township management review, guidelines check, or renovation deposit (e.g. front gate, awning, external grilles).
  - 🔴 **Approval Required (Red)**: Strict statutory compliance under **Act 133 Section 70** (e.g. hacking structural walls, removing beams/columns, boundary extensions requiring PBT & Qualified Person / Engineer plans).

- **📋 Renovation Checklist & Planner**:
  - Select your renovation zones to automatically compile a step-by-step checklist.
  - Deduplicated requirements categorized by **Documents**, **Engineering Plans**, **Deposits**, and **Approvals**.

- **💬 Law & Renovation AI Assistant**:
  - Search or ask questions in plain English (e.g. *"Can I hack down a kitchen wall?"* or *"Do I need permit for an awning?"*).
  - Instant answers backed by statutory citations and Act 133 provisions.

- **👥 Township Community & Notices**:
  - Community feed for renovation tips, contractor recommendations, and official township notices.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript (SPA architecture)
- **Styling**: Tailwind CSS (CDN v3.4), Poppins Typography
- **3D Graphics**: Three.js (r128)
- **Deployment**: Configured for instant deployment on [Vercel](https://vercel.com) or GitHub Pages

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/papa-foxy/HomeWise.git
cd HomeWise
```

### 2. Run locally
Since HomeWise is a lightweight, zero-build single-page application, you can run it directly:

#### Option A: Python HTTP Server
```bash
# Python 3
python -m http.server 3000
```
Open `http://localhost:3000` in your browser.

#### Option B: Node.js (npx serve)
```bash
npx serve .
```

#### Option C: VS Code Live Server
Right-click `index.html` and select **"Open with Live Server"**.

---

## 🌐 Deployment

The project includes [`vercel.json`](./vercel.json) for easy one-click deployments.

### Deploy to Vercel
1. Push your changes to GitHub.
2. Import the repository in [Vercel Dashboard](https://vercel.com).
3. Framework Preset: **Other** (Root directory: `./`).
4. Click **Deploy**.

---

## 📜 Regulatory Citations

Regulations and clauses referenced in HomeWise:
- **Street, Drainage and Building Act 1974 (Act 133)**:
  - *Section 70(1)*: Prohibition against unauthorized erection or alteration of buildings without local authority (PBT) approval.
- **Uniform Building By-Laws 1984 (UBBL)**: Guidelines on structural safety, ventilation, natural lighting, and fire escapes.
- **Township Deed of Mutual Covenants (DMC) & Joint Management Body (JMB) Guidelines**: Specific estate height, facade, and paint restrictions.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
