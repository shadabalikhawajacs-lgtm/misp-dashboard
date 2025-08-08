# 📊 Threat Intelligence Dashboard (Customized Fork)

> Customized by **Shadab Ali Khawaja**  
> 🔗 [GitHub Profile](https://github.com/shadabalikhawajacs-lgtm)  
> 🔗 [LinkedIn](https://www.linkedin.com/in/shadab-ali-khawaja-a032a0369/)

---

## 🔍 Project Overview

This is a customized fork of the [MISP Threat Intelligence Dashboard](https://github.com/MISP/misp-dashboard), used to visualize real-time threat indicators from the MISP platform.

I adapted and modified the project to demonstrate my cybersecurity skills in:

- Threat Intelligence
- Data Visualization
- SOC Analysis and Monitoring

---

## ✨ Key Features

- Real-time feed of indicators (IPs, domains, files)
- Interactive GeoDash-based mapping of threats
- Integration with MISP API
- MITRE ATT&CK tagging support
- Deployment-ready with Python, Flask, and Redis

---

## ⚙️ Technologies Used

- Python (Flask)
- Redis
- MISP API
- GeoDash (JavaScript-based)
- MITRE ATT&CK
- Docker (optional)

---

## 📁 How to Run

```bash
# Clone the repository
git clone https://github.com/shadabalikhawajacs-lgtm/misp-dashboard.git
cd misp-dashboard

# Set up dependencies (example)
pip install -r requirements.txt

# Start Redis server (you must have Redis installed)
redis-server

# Run the Flask app
python3 dashboard.py
