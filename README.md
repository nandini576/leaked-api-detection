# 🔐 API Key Leak Detection Framework

## 📌 Project Overview
The API Key Leak Detection Framework is a cybersecurity-focused system designed to identify exposed API keys, secrets, and credentials from code and text data.

The system analyzes input data to detect potential security leaks, helping developers and organizations prevent unauthorized access, data breaches, and misuse of sensitive information.

---

## 🚀 Key Features
- 🔍 Detects exposed API keys and secrets  
- ⚡ Multi-layer detection (Regex + Entropy + Context Analysis)  
- 🛡️ Risk scoring and classification of detected keys  
- 📊 Structured and interpretable output  
- 🏷️ Service identification (AWS, GCP, Azure, etc.)  
- 🌐 Modular and scalable design  

---

## ⚙️ Workflow

### 1. Input Processing
The system accepts input data (code/text) for analysis.

### 2. Data Preprocessing
Removes unnecessary symbols and normalizes the data to improve detection accuracy.

### 3. Detection Engine
Uses a multi-layer approach:
- Regex Patterns → Detect known API formats  
- Entropy Analysis → Identify secret-like strings  
- Context Analysis → Validate detected credentials  

### 4. Risk Scoring
Assigns a risk score based on type, confidence, and context.

### 5. Classification
Categorizes detected keys into services such as AWS, Azure, GCP, etc.

### 6. Result Output
Displays detected keys along with their risk levels and classifications.

---

## 🔄 System Architecture (Flow)

### A. Input Module  
Handles input data for analysis.

### B. Preprocessing Module  
Cleans and standardizes the input.

### C. Detection Engine  
Applies Regex, Entropy, and Context Analysis.

### D. Risk Scoring Module  
Evaluates severity of detected keys.

### E. Classification Module  
Identifies associated services.

### F. Output Module  
Presents structured results.

---

### 🔁 Overall Flow
Input → Preprocessing → Detection → Risk Scoring → Classification → Output

---

## 🛠️ Tech Stack

- Python  
- Regex (Pattern Matching)  
- NumPy / Math (Entropy Calculation)  
- React / (UI)
- Node js,Express js / (Backend)
- mongoDB (storage)  

---


## 🛠️ Installation & Setup

### 1. Clone Repository
git clone https://github.com/your-username/api-key-leak-detection.git
cd api-key-leak-detection

---

### 2. Backend Setup (Node.js)
cd backend
npm install
npm start

---

### 3. Frontend Setup (React)
cd frontend
npm install
npm start

---

### 4. Python Detection Module
cd detection-module
pip install -r requirements.txt
python detector.py

---

## ▶️ How It Works
- User submits source file through frontend
- Backend processes and sends data to Python module
- Python module detects API leaks using regex, entropy, and context analysis
- Results are returned and displayed on dashboard

## 📈 Future Improvements
- Real-time monitoring of repositories  
- Integration with CI/CD pipelines  
- AI-based detection models  
- Enhanced visualization dashboard  

---

- 📧 Email: nandinikona11@gmail.com  
- 🔗 LinkedIn: https://linkedin.com/in/nandini-kona-89178a31b  

---

## 🤝 Contribution
Developed as part of a team during a hackathon. Contributions and suggestions are welcome.

---

## 📜 License
This project is for educational and research purposes.
