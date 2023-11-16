# Content-Based Image Retrieval (CBIR) System

This repository contains a Content-Based Image Retrieval (CBIR) system implemented in Python using TensorFlow, VGG-16, and Flask. The system is designed to retrieve visually similar images from the Caltech256 dataset.

## Prerequisites

- Python 3.7
- TensorFlow
- Keras
- Flask
- Other dependencies (See `tensorflow.yml` file)

## Dataset

The system uses the [Caltech256 dataset](http://www.vision.caltech.edu/Image_Datasets/Caltech101/). Please download the dataset from the official website.

## How to Execute

1. Open the Jupyter Notebook file `CBIR2.pynb` in a Jupyter Notebook environment.
2. Follow the instructions provided within the notebook to run the CBIR system.

## How to Run the Server

1. Activate the virtual environment (if used).
2. Change the directory to `flaskCBIR`.

    ```bash
    cd flaskCBIR
    ```

3. Run the Flask application using the following command:

    ```bash
    python3 funn.py
    ```

## Usage

1. Visit the home page at [http://localhost:5000/](http://localhost:5000/).
2. Upload an image to find visually similar images from the dataset.
3. Explore the search results and click on images for detailed descriptions.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. Your contributions are highly appreciated!


**Note:** Please ensure that you have the required dependencies installed and have downloaded the Caltech256 dataset before running the system.

Happy image retrieval!
