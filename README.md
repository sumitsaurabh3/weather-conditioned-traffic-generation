# Weather-Conditioned Traffic Image Generation using Latent Diffusion Models

## Overview

This project generates realistic traffic scenes under different weather conditions such as rainy, foggy and nighttime environments using Latent Diffusion Models (LDMs).

## Features

- Traffic image generation
- Weather-conditioned synthesis
- Latent Diffusion Model (LDM)
- Variational Autoencoder (VAE)
- PyTorch implementation

## Dataset

This project uses the ACDC (Adverse Conditions Dataset with Correspondences) dataset.

ACDC contains real-world driving scenes captured under challenging weather and lighting conditions including:

- Fog
- Rain
- Night

The dataset is widely used for autonomous driving and computer vision research in adverse weather environments.

## Pipeline

Traffic Images
→ Preprocessing
→ VAE Encoder
→ Latent Space
→ Diffusion Model
→ Weather Conditioning
→ VAE Decoder
→ Generated Image

## Technologies

- Python
- PyTorch
- NumPy
- OpenCV
- Jupyter Notebook

## Results

### Rainy Weather

<img width="350" height="375" alt="image" src="https://github.com/user-attachments/assets/21f69d59-5cc5-47ad-a7db-5258916ad724" />




### Foggy Weather
<img width="350" height="375" alt="image" src="https://github.com/user-attachments/assets/931632db-10d9-4b0f-bfeb-e87a0d595db8" />











### Night Weather

<img width="350" height="375" alt="image" src="https://github.com/user-attachments/assets/a8e09c5b-3fd4-4d83-9761-9e06e8aaec9b" />


















## Future Work

- More weather conditions
- Higher resolution images
- Video generation
- Autonomous driving simulation
