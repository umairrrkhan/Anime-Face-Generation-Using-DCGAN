# Anime Face Generation Using DCGAN

![Generated Anime Faces](1.png)

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [How it Works](#how-it-works)
- [Usage](#usage)
  - [Training](#training)
  - [Generating Anime Faces](#generating-anime-faces)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Overview

Welcome to the "Anime Face Generation Using DCGAN" project! This repository showcases the application of Deep Convolutional Generative Adversarial Networks (DCGAN) to generate high-quality anime-style faces. DCGANs have demonstrated their ability to create impressive synthetic images, and in this project, we harness this power to craft anime character portraits from scratch.

## Dataset

The heart of any machine learning project is the data it's trained on. For this project, we've included the "Anime Faces Dataset" in the `data/` directory of this repository. This dataset is a rich collection of anime-style face images, containing a substantial number of samples, each with dimensions [insert dimensions].

**Dataset Access:** You can find the Anime Faces Dataset in the `data/` directory of this repository [here](https://www.kaggle.com/datasets/splcher/animefacedataset/code).

## Prerequisites

To run this project successfully, make sure you have the following prerequisites installed on your system:

- Python 
- TensorFlow 
- matplotlib
- numpy 

You can quickly install the necessary packages using `pip`:

## How it Works

Our project employs a DCGAN architecture, a type of generative adversarial network specifically designed for image generation tasks. DCGANs consist of two neural networks: a generator and a discriminator. Here's a brief overview of how the system works:

- Generator: The generator network takes random noise as input and generates synthetic anime face images. Over time, it learns to create more realistic faces.

- Discriminator: The discriminator network acts as a judge, distinguishing between real anime face images from the dataset and fake images generated by the 
                 generator. It provides feedback to the generator on how to improve its generated images.

- The generator and discriminator are trained simultaneously in a competitive manner. This adversarial training process leads to the generation of increasingly 
  convincing anime faces.

## Usage

## Training

Follow these steps to train the DCGAN model on your own:

Clone this Repository:

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/umairrrkhan/Anime-Face-Generation-Using-DCGAN.git
```
Navigate to the Project Directory:

Move into the project directory:

```bash
cd Anime-Face-Generation-Using-DCGAN.ipynb
```

You can monitor the training progress and generated images using TensorBoard or other visualization tools.

## Generating Anime Faces
After training, you can generate anime faces using the trained model:

bash
Copy code
python generate.py
Results
Here's a glimpse of some anime faces generated by our DCGAN model:

## Generated Anime Faces 

![1](my_plot.png)

## Contact

If you have any questions, feedback, or inquiries about this project, don't hesitate to get in touch with us at umairh1819@gmail.com .
