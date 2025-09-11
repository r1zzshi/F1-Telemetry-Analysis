# 🏎️ F1 Telemetry Analysis

**Interactive telemetry & race-data explorer built with FastF1, Pandas, Matplotlib and Jupyter widgets.**  
Polished Stage-1 project for exploring lap times, tyre stints, position changes and basic telemetry — ready for portfolio / LinkedIn / GitHub.

---

## 🔍 Project Summary
This repo contains notebooks and utilities to load official F1 session data (via FastF1), cache it locally, and provide interactive visualizations:
- Position change graphs (lap-by-lap)
- Fastest lap / lap-time comparisons
- Tyre-stint timelines (where available)
- Speed trap / top-speed insights
- Small interactive widgets so others can explore without changing code

---

## ✨ Features
- Interactive widgets to pick drivers / teams / telemetry channels  
- Clean, reproducible notebook structure (Stage 1 + Enhanced)  
- Caching support to speed up repeated runs  
- Exportable `plots/` and reusable analysis cells for portfolio screenshots

---

## 🚀 Quickstart (Windows 11 friendly)

1. Clone repository  
```bash
git clone https://github.com/r1zzshi/F1-Telemetry-Analysis.git
cd F1-Telemetry-Analysis
```
2. (Reccomended) Create & activate a virtual environment
```powershell
# Windows PowerShell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Start Jupyter and open the Enhanced Notebook
```bash
jupyter notebook
# or
jupyter lab
```
5. - Run the top cells first (cache setup, imports, session load).
   - Create a cache/ folder inside the project (some notebooks create it automatically).
   - If a notebook asks for fastf1.Cache.enable_cache('cache'), run that cell before loading sessions.

---

## 👨‍💻 Author
- **Rishi M A**
[Github](https://github.com/r1zzshi) · [LinkedIn](https://www.linkedin.com/in/rishimuthyala/)

---

## ⚡Acknowledgements 
- [FastF1](https://github.com/theOehrly/Fast-F1) for F1 telemetry data access
- Formula 1 community for race data insights and inspiration
- Open-source Python ecosystem: Pandas, Matplotlib, Jupyter
- Daniel Ricciardo <3 my inspiration
  

