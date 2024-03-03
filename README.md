# Text OCR - Text Extraction from Images

This repository contains code for extracting text from images using OCR (Optical Character Recognition). The code is organized into sections for data acquisition, preprocessing, and various OCR techniques applied to images.

## Data Acquisition

The code downloads a dataset from Kaggle using the Kaggle API. It extracts images from the dataset and stores them in the `/kaggle/input` directory.

## Preprocessing

### Annotations
The code loads annotation data from the dataset and visualizes the annotations associated with images.

### Displaying Images
Images from the dataset are displayed using matplotlib. The code visualizes the first 25 images along with their corresponding annotations.

### Preprocessing using OpenCV
OpenCV is used for various preprocessing techniques:

1. **Inverted Images**: The code creates inverted versions of images.
2. **Binarization**: Converts images to black and white.
3. **Noise Removal**: Removes noise from binarized images using morphological operations.
4. **Dilation and Erosion**: Adjusts font sizes in images by applying dilation and erosion operations.

## Instructions for Use

1. Clone the repository.
2. Install the required dependencies.
3. Run the notebook to perform OCR on images.

## Dependencies
- Python 3
- OpenCV
- Matplotlib
- NumPy
- Pandas
- tqdm

## Acknowledgments
- The dataset used in this project is sourced from Kaggle: [Text OCR - Text Extraction from Images Dataset](https://www.kaggle.com/c/textocr-text-extraction-from-images-dataset)

## Author
[Your Name]

## License
This project is licensed under the [MIT License](LICENSE).
