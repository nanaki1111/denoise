NP-SRN: Noise-Level Prior-Guided Selective Reconstruction Network

1. Introduction

This repository provides the implementation of **NP-SRN**, a noise-level prior-guided selective reconstruction network for seismic data denoising.

The proposed method aims to suppress random noise while preserving important seismic reflections and structural details. It incorporates a noise-level estimation strategy and a Selective Reconstruction (SR) Block to improve denoising performance.

2. Network Architecture

The proposed NP-SRN consists of an encoder-decoder architecture with the following components:

Noise-level estimation: Estimates the global noise standard deviation using patch covariance spectral analysis.
SR Block: Performs selective feature reconstruction to enhance useful seismic signals.
MC-SURE loss: Provides a self-supervised training objective without requiring clean reference data.

3. Environment Requirements

The code was developed and tested using the following environment:

- Python 3.9
- PyTorch
- NumPy
- SciPy
- Matplotlib

Recommended hardware:
- NVIDIA GPU
- CUDA-compatible PyTorch environment

Please install the required dependencies before running the code.

4. Repository Structure

NP-SRN
├──main.py
│
├── data
│
├── main_3d.py
│
└── README.md

