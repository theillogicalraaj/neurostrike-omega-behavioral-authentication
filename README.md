# neurostrike-omega-behavioral-authentication
# NeuroStrike Ω++  
### Continuous Behavioral Authentication using Keystroke Dynamics

---

## 📌 Objective
To simulate continuous user authentication using typing behavior (keystroke dynamics) and evaluate user consistency through statistical modeling.

---

## 🧠 Project Overview

NeuroStrike Ω++ is a browser-based simulation of a behavioral biometric system.  
It analyzes typing patterns in real-time and determines whether the current user behavior matches previously learned patterns.

The system uses statistical techniques such as mean, deviation, and variance to calculate trust and risk scores.

---

## ⚙️ System Flow

Input → Feature Extraction → Statistical Analysis → Risk Calculation → Decision Output

---

## 🔍 Features

- Real-time keystroke tracking
- Dwell time and flight time extraction
- Multi-session baseline learning
- Risk and trust scoring system
- Visual representation using graphs
- Clear decision output (Normal / Suspicious)
- Edge-case handling for insufficient data

---

## 📊 Mathematical Model

### Weight Justification:
- **Deviation (50%)** → Primary anomaly indicator  
- **Variance (30%)** → Measures consistency  
- **Speed Factor** → Detects automation behavior  

---

## ⚠️ Decision Rule

- Risk > 60 → Suspicious Behavior  
- Risk ≤ 60 → Normal Behavior  

---

## 📈 Visualization

- Flight time plotted against keystroke sequence  
- Helps observe behavioral consistency  

---

## 🧪 Technologies Used

- HTML  
- CSS  
- JavaScript  

(No external libraries)

---

## 🚫 Limitations

- This is a statistical simulation, not a production system  
- Does not use machine learning models  
- Limited dataset (local session-based learning)  

---

## 🌍 Real-World Applications

- Continuous authentication systems  
- Banking fraud detection  
- Behavioral biometrics  
- Intrusion detection systems  

---

## ▶️ How to Run

1. Download or clone the repository  
2. Open `index.html` in your browser  
3. Start typing to generate behavioral data  

---

## 👨‍💻 Author

Developed as a cybersecurity mini-project focusing on behavioral authentication and system design principles.

---

## 📌 Note

This project is intended for educational purposes to demonstrate statistical modeling in cybersecurity systems.
