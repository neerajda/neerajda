# Hi, I'm Neeraj - I build ML systems that keep trucks on the road 

**Data Scientist @ TensorPlanet** · Predictive Maintenance · Fleet Telematics · Industrial AI

---

Most ML models die in Jupyter notebooks. Mine run every morning at 6 AM, decide which of 500+ commercial vehicles need a mechanic today, and email the fleet manager before their coffee gets cold.

I work at the unglamorous intersection of diesel engines and data pipelines — turning raw J1939 fault codes, odometer streams, and maintenance work orders into alerts that mechanics actually trust. Before this, I taught neural networks to find corrosion in industrial parts at Renault Nissan's R&D center.

---

## What I Work With

**Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Visualization & Apps**

![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)

**Computer Vision & 3D**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PointNet](https://img.shields.io/badge/PointNet-3D_Segmentation-orange?style=flat-square)
![CNN/RNN/GNN](https://img.shields.io/badge/CNN·RNN·GNN-Deep_Learning-red?style=flat-square)

---

## Numbers I'm Accountable For

- **500+ vehicles** monitored daily across 5+ enterprise fleet clients — every alert my pipeline fires either saves a breakdown or wastes a mechanic's morning. The recall validation framework I built keeps score.
- **24,000+ diagnostic records** processed per pipeline run through configurable rule engines — DEF, DPF, EGR, and NOx fault models, each with its own YAML-defined thresholds, co-signal logic, and lookback windows.
- **1,900+ real work orders** used as ground truth to validate whether our alerts actually predicted the failures mechanics ended up fixing. Turns out honest evaluation is harder than modeling.
- **86 vehicles** flagged for overdue DOT inspections in a single client audit — 70 of them were more than a month overdue. Compliance teams love spreadsheets that write themselves.
- **30% reduction** in manual evaluation time from a GenAI-powered project tracker I built during my IIT Madras degree — GitHub API in, progress assessments out.

---

## Things I've Built

###  Fleet Fault Radar
**Python · pandas · PostgreSQL · YAML rule engines · Plotly**

A multi-model alert platform that reads J1939 fault codes from truck telemetry and decides which vehicles need attention — before they break down on the interstate. Each component model (DEF, DPF, EGR, NOx) is a config file, not a code change.

*Why it matters: unplanned downtime for a commercial truck costs $500–$1,000 per day. Catching a failing NOx sensor a week early pays for the entire system.*

###  Work-Order Truth Machine
**Python · VIN-level entity matching · precision/recall analytics**

A validation framework that answers the question every ML team avoids: "did our alerts actually predict anything?" Matches every alert against real maintenance records and diagnoses every miss — was the threshold too strict, or is the model blind to that failure mode?

*Why it matters: a fault model nobody validates is a random number generator with a dashboard.*

###  Samsara Sync Engine
**Python · REST APIs · batch orchestration · idempotent DB writes**

An ingestion pipeline that pulls odometer, battery, and GPS telemetry for entire fleets from the Samsara API — batched, deduplicated, and resumable. Computes daily utilization, moving-day detection, and mileage analytics per vehicle.

*Why it matters: every downstream model is only as good as the telemetry pipeline feeding it. This one doesn't drop data when the API hiccups.*

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=neerajda&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=neerajda&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="165">
</p>

---

## Elsewhere

📍 IIT Madras, B.S. Data Science (Class of 2025)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/neeraj-yadav-50b572198)
[![Email](https://img.shields.io/badge/Email-neerajbill90@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:neerajbill90@gmail.com)


---

*Currently interested in: streaming feature pipelines, model development and deployment 
