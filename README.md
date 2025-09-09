

# 📸 Image Resolution Enhancer

## 📝 Description

**Image Resolution Enhancer** is a powerful Python-based tool that uses deep learning to increase the resolution of images without losing quality. It's designed to make images clearer, sharper, and more detailed, whether you're working with old photos, blurry pictures, or low-resolution graphics.

## 🚀 Features

  * **Super-Resolution**: Upscale images using state-of-the-art deep learning models (e.g., ESRGAN, SRCNN).
  * **Batch Processing**: Enhance multiple images at once.
  * **Easy to Use**: A simple command-line interface makes it accessible for both developers and casual users.
  * **Customizable**: Adjust model parameters and output settings for different types of images.
  * **Cross-Platform**: Works on Windows, macOS, and Linux.

## ⚙️ Installation

### Prerequisites

  * Python 3.8 or higher
  * pip

### Steps

1.  **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/image-resolution-enhancer.git
    cd image-resolution-enhancer
    ```

2.  **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Download a Pre-trained Model**
    Download a pre-trained model (e.g., `esrgan-x4.pth`) from a reputable source and place it in the `models/` directory.

## 📖 Usage

### Command-Line Interface

To enhance a single image:

```bash
python enhancer.py --input_image path/to/your/image.jpg --output_image path/to/save/upscaled_image.png --model models/esrgan-x4.pth
```

To process a directory of images:

```bash
python enhancer.py --input_dir path/to/your/images/ --output_dir path/to/save/upscaled_images/ --model models/esrgan-x4.pth
```

### Options

| Flag | Description | Default |
| :--- | :--- | :--- |
| `--input_image` | Path to a single input image. | None |
| `--input_dir` | Path to a directory of input images. | None |
| `--output_image` | Path to save the enhanced output image. | `output.png` |
| `--output_dir` | Path to save the enhanced images. | `output/` |
| `--model` | Path to the pre-trained deep learning model. | None |

## 🤝 Contributing

Contributions are welcome\! Please feel free to open a pull request or submit an issue on the GitHub repository.

## 📜 License

This project is licensed under the MIT License.
