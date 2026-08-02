# 🚁 Drone-Based Disaster Relief Distribution Optimization

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-KMeans-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![NetworkX](https://img.shields.io/badge/NetworkX-Graph%20Analysis-informational)](https://networkx.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An optimization system that plans the most efficient distribution of relief supplies via drones in the aftermath of an earthquake.
The system combines **K-Means clustering**, **Dijkstra's shortest path algorithm**, and the **NetworkX** graph library to:

- Cluster demand points based on need
- Determine the optimal warehouse/depot for each cluster
- Compute the shortest delivery route
- Plan distribution according to drone capacity

## 📑 Table of Contents

- [Purpose](#-purpose)
- [Tech Stack](#-tech-stack)
- [How It Works](#-how-it-works)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Future Improvements](#-future-improvements)
- [Authors](#-authors)

## 🎯 Purpose

The goal of this project is to enable fast, planned, and optimized relief distribution after a disaster by:

- Minimizing delivery time
- Making efficient use of drone capacity
- Ensuring relief supplies reach high-priority need zones on time

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core language |
| **Pandas** | Data processing |
| **NumPy** | Mathematical computations |
| **Scikit-learn (KMeans)** | Clustering algorithm |
| **NetworkX** | Graph structure and shortest-path analysis |

## ⚙️ How It Works

1. Data is loaded from Excel files (demand points and distance matrix).
2. Demand points are clustered using K-Means.
3. The nearest depot is determined for each cluster.
4. The shortest route is calculated using Dijkstra's algorithm.
5. A distribution plan is generated based on drone capacity.

## 📂 Project Structure

```
drone-based-disaster-relief-optimization/
│
├── report.docx              → Project report
├── demand-table.xlsx        → Demand point data
├── distance-table.xlsx      → Distance matrix
└── main.py                  → Main Python script
```

## 🚀 Getting Started

1. Install the required libraries:

```bash
pip install pandas numpy scikit-learn networkx
```

2. Run the script:

```bash
python main.py
```

## 🔮 Future Improvements

- Dynamic route updates using real-time GPS data
- Incorporating weather data into route planning
- Route optimization based on drone battery level
- Adding map-based visualization

## 👥 Authors

This project was built as a team effort by:

- **Esmanur Yıldız**
- **Sedanur Peker**
