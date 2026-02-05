# 🌊 Urban Flood Prediction & Smart Drainage System

### Using CNN–LSTM Deep Learning Model

## 📌 Overview

Urban flooding is a critical problem in modern cities caused by heavy rainfall, inefficient drainage systems, and rapid urbanization.
This project proposes an **AI-based Urban Flood Prediction and Drainage Analysis System** using a **hybrid CNN–LSTM model** to predict flood risk and identify drainage inefficiencies in urban areas.

The system analyzes **spatial data** (urban layout, elevation, drainage network) and **temporal data** (rainfall over time) to provide accurate, early flood predictions.

---

## 🚨 Problem Statement

* Urban areas frequently experience flooding during heavy rainfall.
* Existing prediction systems are often:

  * Reactive rather than proactive
  * Unable to capture complex spatial–temporal relationships
* Poor drainage design and lack of real-time prediction increase damage to life, property, and infrastructure.

---

## 🎯 Objectives

* Predict **urban flood risk in advance** using deep learning.
* Analyze **drainage system efficiency** across city zones.
* Generate **risk maps and early alerts** for decision-makers and emergency responders.

---

## 🧠 Why CNN–LSTM?

Urban flooding depends on both **where** and **when** rainfall occurs.

* **CNN (Convolutional Neural Network):**

  * Extracts spatial features from satellite images, elevation maps, and drainage layouts.
* **LSTM (Long Short-Term Memory):**

  * Learns temporal patterns from rainfall and climate time-series data.

🔗 **CNN captures the city structure, LSTM remembers the rainfall history.**

---

## 🗂️ Datasets Used

* **NASA GPM (Global Precipitation Measurement):**
  Rainfall intensity and distribution data.
* **Digital Elevation Model (DEM):**
  Terrain and slope information affecting water flow.
* **Urban Drainage Network Data:**
  Drainage canals, pipelines, and road layouts.
* **Historical Flood Records:**
  Past flood event data for model validation.
* **Climate Data:**
  Temperature, humidity, and related environmental parameters.

---

## ⚙️ Methodology

1. **Data Preprocessing**

   * Data normalization and cleaning
   * Temporal alignment of rainfall sequences
   * Spatial data resizing for CNN input

2. **Model Architecture**

   * CNN layers for spatial feature extraction
   * LSTM layers for temporal dependency learning
   * Fully connected layers for flood risk prediction

3. **Training & Evaluation**

   * Train–validation–test split: 70% / 20% / 10%
   * Evaluation metrics:

     * Accuracy
     * Precision
     * Recall
     * F1-score

---

## 📤 Output

* Flood risk classification:

  * **High Risk**
  * **Medium Risk**
  * **Low Risk**
* City-level flood risk maps
* Drainage system performance insights
* Early warning indicators for extreme rainfall events

---

## 📈 Results

* Achieved **high prediction accuracy (~90%+)** compared to traditional models.
* Successfully identified flood-prone urban zones.
* Demonstrated the effectiveness of hybrid deep learning for urban flood management.

---

## 🌍 Impact

* Reduces flood-related damage and economic loss.
* Assists city planners in improving drainage infrastructure.
* Supports disaster preparedness and emergency response systems.
* Contributes toward **smart and resilient cities**.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / PyTorch
* CNN & LSTM Neural Networks
* GIS & Satellite Data
* NumPy, Pandas, Matplotlib

---

## 🚀 Future Improvements

* Real-time IoT sensor integration
* Mobile/web-based alert system
* Integration with smart city dashboards
* Higher-resolution satellite imagery support

