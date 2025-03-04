# 🌾 Mixed Pixel Detection in Thermal Images for Precision Agriculture

## 👨‍💻 Team Members:
- [**Sachin SM**](https://github.com/sachin02-hub)
- [**Sarang S Nair**](https://github.com/sarangs1621)
- [**Shradha Saji**](https://github.com/ShradhaShaji)
- [**Anaswer Ajay**](https://github.com/imanaswer)
- **Mentor**: [**Sarath S**](https://github.com/sarath444)

---

## 📜 Project Overview
This project tackles the **Mixed Pixel Problem** in thermal imaging, enhancing precision agriculture through artificial intelligence. The aim is to detect mixed pixels in thermal images, quantify their proportion, and improve early disease detection in crops.

### 🌟 Highlights
- **Mixed Pixel Detection Algorithm**: Autoencoder-based deep learning framework.
- **Custom Dataset**: Includes labeled thermal images of healthy and diseased crops.
- **Performance Metrics**:
  - **Mixed Pixel Percentage (MPP)**: `5.58%`
  - **SSIM**: `0.8905`
  - **MSE**: `0.0028`
- **Scalable Design**: Adapts to diverse crops and environments.

---

## 🛠️ Methodology
1. **Data Preprocessing**:
   - Augment dataset size through transformations.
   - Resize and normalize images for uniformity.
2. **Deep Learning Model**:
   - **CNN-Based Autoencoder** for unsupervised learning.
   - Mixed pixel identification via reconstruction errors.
3. **Validation**:
   - Tested across varying environmental conditions.
   - Evaluated using **MPP**, **SSIM**, and **MSE**.

---

## 🔍 High-Level System Design
1. **Input**: High-resolution thermal images.
2. **Preprocessing**: Data augmentation, normalization, resizing.
3. **Model**: CNN-based Autoencoder for pixel-level analysis.
4. **Output**: Visual representation and quantitative metrics of mixed pixels.


---

## Architectural Design
![Architecture (1)](https://github.com/user-attachments/assets/0f35eb7c-3420-4fe7-b4e7-dd13e632cef7)

---

## Block Diagram
![Input Images (1)](https://github.com/user-attachments/assets/309b85b4-074a-41ca-8964-efea49f88745)

---

## 🎯 Results & Findings
- **Visual Detection**: Successfully identified and highlighted mixed pixels.
- **Quantitative Metrics**: Achieved robust and scalable performance metrics:
  - **MPP**: 5.58%
  - **SSIM**: 0.8905
  - **MSE**: 0.0028
- **Robustness**: Strong generalization under diverse conditions.
- 
  ![Screenshot 2025-03-04 141609](https://github.com/user-attachments/assets/edc8284c-8eef-42c5-9fe8-2b2f38ce2cb5)



### ✨ Key Takeaway
Combining **AI** and **thermal imaging** offers a scalable, cost-effective solution for precision agriculture.

---

## 🧪 Experimental Setup
### Dataset:
- High-resolution thermal images captured under controlled conditions.
- Metadata includes plant type, disease, and environmental settings.

### Validation Metrics:
- **Mixed Pixel Percentage (MPP)**: Measures pixel ambiguity.
- **SSIM**: Evaluates image reconstruction quality.
- **MSE**: Measures reconstruction error.

### Robustness Testing:
- Simulated various environmental conditions.
- Added synthetic noise to test algorithm resilience.

### Results Table:
#### Image 1:
| **Metrics**               | **Values** |
|---------------------------|------------|
| Mixed Pixel Percentage    | 5.58%      |
| SSIM                      | 0.8905     |
| MSE                       | 0.0028     |

#### Image 2:
| **Metrics**               | **Values** |
|---------------------------|------------|
| Mixed Pixel Percentage    | 5.53%      |
| SSIM                      | 0.8339     |
| MSE                       | 0.0028     |

---

## ⚠️ Limitations
1. Dataset limited to specific plant types.
2. High-resolution thermal cameras required.
3. Computational demands for real-time applications.
4. Complex model interpretability for non-experts.

---

## 🔮 Future Scope
1. **Expanded Dataset**: Include diverse crops, diseases, and environments.
2. **Algorithm Optimization**: Develop lightweight models for edge devices.
3. **Advanced Segmentation**: Leverage transformers or graph-based models.
4. **Real-World Validation**: Conduct large-scale field trials.
5. **User-Friendly Interfaces**: Create tools accessible to non-technical users.
---

## 🚀 How to Use
1. **Clone the repository**:
   ```bash
   git clone https://github.com/sarangs1621/Detection-of-Mixed-Pixels-in-Thermal-Image.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd mixed-pixel-detection
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the model**:
   ```bash
   python Thermal.ipynb
   ```
---

## 📂 Repository Structure
```
|-- dataset/
|   |-- images/
|   |-- labels.csv
|-- models/
|   |-- autoencoder.py
|-- results/
|   |-- output_images/
|-- Thermal.ipynb
|-- README.md
|-- requirements.txt
```
---

## 📋 Requirements
### 🛠️ Dependencies:
- **Python 3.8+**
- **TensorFlow 2.x**
- **NumPy**
- **Matplotlib**
- **scikit-learn**
- **OpenCV**

To install all dependencies, run:
```bash
pip install -r requirements.txt
```
---

## 📚 References
1. **Jones, H. G., & Sirault, X. R. R.** (2014). Scaling of Thermal Images at Different Spatial Resolutions: The Mixed Pixel Problem. *Agronomy*, 4(3), 380–396. [DOI: 10.3390/agronomy4030380]
2. **Santos, L., et al.** (2020). Analyzing the Effect of Spectral Interference of Mixed Pixels. *IEEE JSTARS*. [DOI: 10.1109/JSTARS.2020.3045712]
3. **Bovolo, F., et al.** (2010). Subpixel Image Classification Based on SVM. *IEEE Transactions on Image Processing*. [DOI: 10.1109/TIP.2010.2051632]

---

## 🤝 Contribution
Feel free to submit issues and pull requests to enhance the project. For queries, reach out through the **Issues** section of this repository.

---


