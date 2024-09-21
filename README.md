
# NYC Taxi Trip Duration Predictions

## Project Overview

This project focuses on predicting the duration of taxi trips in New York City using advanced deep learning models. Several architectures, including AutoEncoders, LSTM-Transformer hybrid models, and VGG16-ResNet models, are used to process the data and make accurate predictions. The project leverages deep learning techniques for time-series and image-based data processing.

## Technology Stack

- **Python**: Core programming language.
- **TensorFlow/Keras**: For implementing deep learning models such as AutoEncoders, LSTM, Transformers, VGG16, and ResNet.
- **Pandas & NumPy**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For data visualization and plotting.
- **Jupyter Notebooks**: For interactive model development and experimentation.

## Project Structure

- `AutoEncoders.ipynb`: Jupyter Notebook implementing an AutoEncoder model.
- `LSTM Transformer Model.ipynb`: Jupyter Notebook implementing a hybrid LSTM-Transformer model.
- `VGG16 ResNet.ipynb`: Jupyter Notebook implementing a VGG16-ResNet model.
- `AutoEncoders Model.h5`: Pre-trained AutoEncoder model saved in HDF5 format.
- `Dataset.txt`: Information about the dataset used in this project.
- `Report.pdf`: A detailed report explaining the project goals, methodology, and results.

## Installation Instructions

### Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

### Steps

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd NYC-Taxi-Trip-Duration-Predictions
   ```

2. Create and activate a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install tensorflow keras pandas numpy matplotlib seaborn
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open any of the model notebooks (`AutoEncoders.ipynb`, `LSTM Transformer Model.ipynb`, `VGG16 ResNet.ipynb`) and run the cells to train or evaluate the models.

## Usage

Each notebook can be used to train, fine-tune, or evaluate the corresponding models for predicting NYC taxi trip durations. The dataset information is provided in `Dataset.txt`, and the pre-trained AutoEncoder model is stored in the `AutoEncoders Model.h5` file.

The notebooks contain detailed instructions and explanations of each model's architecture and how to run them.
