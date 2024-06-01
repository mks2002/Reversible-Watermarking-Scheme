# Reversible Watermarking Scheme

This repository contains the implementation of a reversible watermarking scheme for image content authentication based on wavelet transform. The implementation is based on the paper "[A reversible watermarking for image content authentication based on wavelet transform](https://link.springer.com/article/10.1007/s11760-023-02950-z)" by De Li, Xianlong Dai, Jiang Gui, Jinyan Liu, and Xun Jin.

## Repository Structure

The repository contains the following files:

- **Images**:

  - `baboon-color.jpg`: Sample color image of a baboon used in the experiments.m
  - `baboon.jpg`: Sample grayscale image of a baboon used in the experiments.
  - `leena-color.png`: Sample color image of Lena used in the experiments.
  - `Lena-gray.png`: Sample grayscale image of Lena used in the experiments.

- **Jupyter Notebooks**:
  - `watermark-embedding-extraction-color-baboon.ipynb`: Notebook for watermark embedding and extraction in color baboon image.
  - `Watermark-embedding-extraction-gray-baboon.ipynb`: Notebook for watermark embedding and extraction in grayscale baboon image.
  - `Watermark-embedding-extraction-gray-leena.ipynb`: Notebook for watermark embedding and extraction in grayscale Lena image.
  - `watermark-embeding-extraction-for-color-Leena.ipynb`: Notebook for watermark embedding and extraction in color Lena image.

## Requirements

To run the code in this repository, you need the following libraries:

- `numpy`
- `opencv-python`
- `pywt`
- `pillow`
- `google-colab`

You can install these libraries using pip:

```bash
pip install numpy opencv-python pywt pillow google-colab
```
