# ☁️ Cloud Monitoring System

A basic cloud resource monitoring system developed using **Google Colab and Python**. The system monitors CPU, memory, disk, and network-related metrics and identifies abnormal resource utilization using predefined thresholds.

## 🚀 Features

- Monitor CPU utilization
- Monitor memory utilization
- Monitor disk utilization
- Monitor network activity
- Detect high resource usage
- Generate server health status
- Visualize resource utilization
- Interactive Gradio monitoring interface

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Psutil
- Gradio

## ☁️ Cloud Computing Concept

Google Colab provides the cloud-based execution environment for the project.

The system collects resource utilization metrics from the running cloud environment and analyzes them using a monitoring engine.

Threshold-based alerts are generated when resource utilization becomes high.

## 🏗️ System Architecture

```text
              Cloud Environment
                     │
                     ▼
              Resource Monitor
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
       CPU          RAM          Disk
        │            │            │
        └────────────┼────────────┘
                     ▼
             Monitoring Engine
                     │
              ┌──────┴──────┐
              ▼             ▼
           Healthy        Warning
              │             │
              🟢            🚨
```

## 📊 Monitoring Thresholds

| Resource | Threshold | Status |
|---|---:|---|
| CPU | > 80% | Warning |
| Memory | > 80% | Warning |
| Disk | > 90% | Warning |

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install the required Python libraries.
3. Run the monitoring cells.
4. Collect system resource metrics.
5. Generate monitoring graphs.
6. Launch the Gradio interface.
7. Check the cloud environment's health status.

## 📁 Project Structure

```text
cloud-monitoring-system/
│
├── Cloud_Monitoring_System.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🔮 Future Enhancements

- Real-time monitoring dashboard
- Multiple cloud server monitoring
- Email/SMS alerts
- Historical monitoring database
- Automatic resource scaling
- Cloud deployment
- Prometheus/Grafana integration
- Machine-learning-based anomaly detection

## 👩‍💻 Author

**Rania**

Cloud Computing Project
