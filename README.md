# BirdSoundClassifier

## Overview
This project is a machine learning pipeline for classifying bird sounds recorded in the Pacific Northwest (PNW) using audio signals. The dataset includes various bird species identified by their unique calls.

## Features
- Preprocessing of audio data into spectrograms.
- Implementation of Dense Neural Networks and Convolutional Neural Networks for classification.
- Visualization of training and validation accuracy over epochs.
- Use of spectrograms for enhanced feature extraction and classification.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rnhggrwl/BirdSoundClassifier.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset used in this project includes metadata from eBird.org. Audio files should be organized as follows:
```
data/
├── train/
├── test/
```

## How to Run
1. Load the train and test datasets by specifying paths in the script.
2. Train the model:
   ```bash
   python train_model.py
   ```
3. Evaluate the model:
   ```bash
   python evaluate_model.py
   ```

## Results
- Achieved an accuracy of ~90-95% on the test dataset.
- Included visualizations of training and test accuracy over epochs.

## Key Files
- **main.ipynb**: Jupyter notebook containing the full pipeline.
- **models.py**: Model architectures for DenseNet and CNN.
- **utils.py**: Utility functions for data preprocessing and visualization.

## Future Improvements
- Optimize CNN architecture for better accuracy.
- Explore additional bird species for classification.
- Enhance real-time classification capabilities.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

