<div align="center">
  <h1 style="color: #f5f5f5;">Malaria Detection Using Blood Smear Images</h1>
  <p style="color: #b0b0b0;">Leveraging CNNs for accurate classification of parasitized and uninfected cells</p>
</div>

## 📜 Project Overview

Malaria is a life-threatening disease caused by *Plasmodium* parasites, and rapid, accurate diagnosis is crucial for effective treatment. In this project, we developed a **Convolutional Neural Network (CNN)** model to automate the detection of malaria-infected cells using blood smear images. By training the model on the **Malaria Cell Images Dataset**, we achieved **94.5% accuracy**, showcasing the potential of deep learning in medical diagnostics.

## 📊 Model Architecture

Our CNN architecture is designed to automatically learn hierarchical features from input images, making it highly effective for image classification tasks. The key components of the model are:

- **Convolutional Layers**: Extract hierarchical features.
- **Max-Pooling Layers**: Reduce dimensionality while preserving key features.
- **Dense Layers**: Perform classification based on learned features.
- **Dropout**: Prevents overfitting and improves generalization.

## 🛠️ Tools & Libraries

- **TensorFlow** & **Keras**: Model development and training.
- **Matplotlib**: Visualization of training progress.
- **EMR & SageMaker**: Model deployment.
- **MLflow**: Model tracking and artifact management.

## 🧬 Dataset

The dataset contains **27,558 cell images** split evenly between parasitized and uninfected cells, sourced from **thin blood smear slides**. Each image was resized to 130x130 pixels and normalized for training. [Access the dataset here](https://www.tensorflow.org/datasets/catalog/malaria).

## 📈 Results

The model was trained for 80 epochs, and performance was evaluated using accuracy and loss metrics for both training and validation sets. Here's an overview of the model's performance:

- **Training Accuracy**: 95.2%
- **Validation Accuracy**: 93.8%
- **Test Accuracy**: 94.5%

### Sample Image Results:
![Malaria Cell Images](https://github.com/priyanka-senthil/Malaria-Parasite-Detection/raw/main/malaria-1.0.0.png)

## 🚀 Future Scope

- **Larger datasets** for more robust generalization.
- **Transfer learning** with pre-trained models like **VGG19**.
- **Real-time malaria detection** through mobile or web applications.

## 📚 References

- Sivaramakrishnan Rajaraman et al., **Pre-trained CNNs for Malaria Detection**, PeerJ, 2018. [Link](https://peerj.com/articles/4568)
- TensorFlow Datasets, **Malaria Dataset**. [Link](https://www.tensorflow.org/datasets/catalog/malaria)

---

<div align="center">
  <h3 style="color: #f5f5f5;">Contributors</h3>
  <p style="color: #b0b0b0;">Priyanka Senthil Kumar, Sharayu Shekhar Thosar, Song Ruifeng</p>
  <p style="color: #808080;">Northeastern University</p>
</div>
