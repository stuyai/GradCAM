# GradCam Project

This project implements Grad-CAM (Gradient-weighted Class Activation Mapping) for visualizing and understanding convolutional neural networks.

## Overview

Grad-CAM is a technique that provides visual explanations for predictions made by deep learning models. It highlights the important regions in an input image that influence the model's decisions.

## Contents

- `COPY_OF_GRAD_CAM_TRAINING_TUTORIAL.ipynb`: Jupyter Notebook containing the implementation and training tutorial.
- `data.csv`: Dataset with cool dog images.

## Requirements

- Python 3.x
- Necessary libraries as specified in the notebook (e.g., TensorFlow or PyTorch, NumPy, Matplotlib)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/stuyai/GradCam.git
    ```

2. Navigate to the project directory:

    ```bash
    cd GradCam
    ```

3. Install required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook:

    ```bash
    jupyter notebook COPY_OF_GRAD_CAM_TRAINING_TUTORIAL.ipynb
    ```

5. Follow the instructions in the notebook to train the model and generate Grad-CAM visualizations.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization](https://arxiv.org/abs/1610.02391)
- The blog post on the slides