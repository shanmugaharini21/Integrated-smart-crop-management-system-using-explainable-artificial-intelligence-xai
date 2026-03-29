# Integrated Smart Crop Management System using Explainable AI (XAI)
A full-stack, AI-driven decision support system for early crop stress prediction using multimodal data fusion and Explainable AI (XAI). The system integrates soil parameters, real-time weather data, and farmer observations to generate accurate, interpretable predictions, enabling proactive and data-driven agricultural decision-making.

# Objectives
🔹 Enable early prediction of crop stress (water, heat, nutrient)
🔹 Leverage multimodal data (structured + unstructured)
🔹 Ensure model transparency using Explainable AI (SHAP)
🔹 Deliver a scalable full-stack web application for real-world use

# Intelligence & Modeling Framework
🔹 Models: Random Forest, XGBoost (ensemble learning)
🔹 Multimodal Fusion: Soil + Weather + Text features
🔹 NLP: TextBlob for extracting insights from farmer notes
🔹 Model Optimization: Grid Search, Cross Validation
🔹 Explainability: SHAP-based feature attribution
🔹 Forecasting: 7–10 day crop stress prediction

The system captures complex, non-linear relationships across heterogeneous data sources, improving prediction reliability.

# Core Capabilities
🔹 Crop Stress Prediction

Predicts water, heat, and nutrient stress using ensemble ML models trained on fused data inputs.

🔹 Multimodal Intelligence

Combines:

Soil nutrients (N, P, K, pH, moisture)
Weather variables (temperature, rainfall, humidity)
Farmer observations (textual inputs)
🔹 Explainable AI (XAI)

Provides interpretable outputs by highlighting key contributing features, improving trust and usability.

🔹 Full-Stack System
Interactive dashboard for insights and monitoring
RESTful backend for model inference
Responsive frontend for real-time interaction

# System Architecture

Input Layer → Soil Data | Weather API | Farmer Notes
Processing Layer → NLP + Feature Engineering + Fusion
Model Layer → Random Forest / XGBoost
XAI Layer → SHAP Interpretability
Output Layer → Dashboard | Insights | Reports

# Tech Stack

AI / Data Science: Python, Scikit-learn, XGBoost, SHAP
NLP: TextBlob
Frontend: React.js
Backend: Flask (REST APIs)
Database: MySQL
Integration: Weather APIs, OCR (pdfplumber)

# Screenshots
<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/80b8cfed-d19a-4f0b-8475-1d2d5665c01d" width="500"/><br>
      <em>Field Creation Interface</em>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/58355ff7-540d-442b-a91c-3553397e528b" width="500"/><br>
      <em>Dashboard & Data Entry</em>
    </td>
  </tr>
</table>


# Results
🔹Accuracy: ~92% (XGBoost)
🔹Improved performance through multimodal data fusion
🔹Strong recall ensures early stress detection

# Impact

Enables early intervention, reduces crop loss, and delivers a transparent, data-driven solution for precision agriculture.

# Acknowledgement

Developed with guidance from academic mentors and supported by open-source AI frameworks and tools.
