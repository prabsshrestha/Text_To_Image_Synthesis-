# 🧠 Text to Image Synthesis using GAN

This project explores **Text-to-Image Synthesis** using **Generative Adversarial Networks (GANs)**. Given a textual description, the model generates a corresponding realistic image.

> "Turning words into visuals using deep learning."

## 🔗 Google Colab Demo

You can try it directly on Google Colab:  
[🚀 Open in Colab](https://colab.research.google.com/drive/1Jwx2BdraV-0E-kpgBdszXetF1Au4UaGZ?usp=sharing)


## 📌 Features

- Text embedding using pre-trained models
- Deep Convolutional GAN architecture (DCGAN)
- Image generation from descriptive captions
- Preprocessing of image-caption datasets
- Visualization of generated images


## 🛠️ Technologies Used

- Python
- PyTorch
- GAN (DCGAN architecture)
- NLTK (for text processing)
- Matplotlib (for visualization)
- Google Colab (for GPU training)

## 📁 Dataset

This project uses a subset of the [Caltech-UCSD Birds 200](http://www.vision.caltech.edu/visipedia/CUB-200.html) dataset with textual captions.

## 🧪 How It Works

1. **Text descriptions** are embedded into vector representations.
2. These vectors are passed through a **Generator** network.
3. The **Discriminator** tries to distinguish between real and generated images.
4. The system improves via adversarial training until realistic images are produced.


