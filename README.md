# SAR Image Colorization for Comprehensive Insights Using Deep Learning

![SAR Colorization Banner](https://your-placeholder-banner-link.com)

## 📌 Overview

**SAR (Synthetic Aperture Radar) images**, widely used in remote sensing, are typically grayscale and lack the visual richness needed for human interpretation. This project aims to enhance the **interpretability** and **visual appeal** of SAR images by transforming them into realistic **color images** using **deep learning models**.

We utilize a **CycleGAN** architecture to learn mappings between grayscale SAR domains and their colored counterparts, enabling more effective analysis for environmental monitoring, land use classification, disaster assessment, and more.

## 🎯 Objectives

- 🌈 Transform grayscale SAR images into colored images
- 🧠 Leverage deep learning models (CycleGAN) for image-to-image translation
- 🔬 Aid remote sensing applications with visually interpretable data
- 📊 Enhance insight generation from satellite and aerial data

## 🧰 Tech Stack

| Component      | Tools & Libraries                         |
|----------------|-------------------------------------------|
| Framework      | Python, OpenCV, NumPy                     |
| Deep Learning  | PyTorch, torchvision                      |
| GAN Model      | CycleGAN                                  |
| Deployment     | Streamlit                                 |
| Visualization  | Matplotlib, PIL                           |

## 📁 Project Structure

```
sar_image_colorization/
├── models/
│   └── models_colorization_deploy_v2.prototxt
├── test_images/
├── app.py
├── utils.py
├── requirements.txt
└── README.md
```

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/vinayak598/sar_image_colorization.git
   cd sar_image_colorization
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # For Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download pre-trained model weights**
   > Place the model `.prototxt` and `.caffemodel` or other formats in the `models/` directory.

5. **Run the application**
   ```bash
   streamlit run app.py
   ```

## 📸 Sample Results

| Input SAR Image | Colorized Output |
|------------------|------------------|
| ![](test_images/sar1.png) | ![](results/color_sar1.png) |
| ![](test_images/sar2.png) | ![](results/color_sar2.png) |

## 📚 Model Details

- **CycleGAN**: An unpaired image-to-image translation architecture that learns mappings between domains using cycle-consistency loss.
- **Loss Functions**: Cycle-consistency, adversarial, identity losses.

## 📈 Applications

- 🌍 Environmental monitoring
- 🛰️ Satellite image analysis
- 🌪️ Disaster response & damage detection
- 🌾 Agricultural land classification
- 🌊 Flood and water body detection

## 👨‍💻 Contributors

- **Josyula Venkata Ramachandra Vinayak** (Team Lead)
- 🏫 **Department of Computer Science and Engineering**, AVN Institute of Engineering and Technology

## 📃 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

For queries, collaborations, or demo requests, reach out via:  
📧 `rcvinayakjv@gmail.com`  
🔗 [LinkedIn](https://www.linkedin.com/in/vinayak598)
