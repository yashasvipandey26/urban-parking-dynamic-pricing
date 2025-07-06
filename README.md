# Dynamic Pricing for Urban Parking Lots

Capstone Project — Summer Analytics 2025  
By: Yashasvi Pandey

---

## 📌 Overview

This project implements a dynamic pricing engine for 14 urban parking lots using real-time data. It adjusts prices based on occupancy, traffic, queue length, vehicle type, and special events to improve space utilization and reduce congestion.

---

## 🧰 Tech Stack

- **Python**
- **Pandas, NumPy** — for data processing
- **Pathway** — for real-time stream simulation and computation
- **Bokeh** — for interactive visualizations
- **Google Colab** — as the development environment

---

## 🧠 Architecture Diagram

```mermaid
flowchart TD
    A[CSV Dataset] --> B[Data Preprocessing]
    B --> C1[Model 1: Baseline]
    B --> C2[Model 2: Demand-Based]
    C1 --> D[Price Output]
    C2 --> D
    D --> E[Pathway Real-Time Pipeline]
    E --> F[Bokeh Visualizations]
