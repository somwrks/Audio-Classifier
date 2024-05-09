# Audio Classifier Project

This project implements an audio classifier using TensorFlow and Keras to classify audio clips as either capuchin bird calls or not.

## Contents

- `main.ipynb`: Jupyter Notebook containing the code for the audio classifier.
- `data/`: Directory containing audio files for training and testing.
- `results.csv`: CSV file containing the classification results.

## Requirements

- Python 3.x
- TensorFlow
- TensorFlow IO
- Librosa
- Matplotlib

## Usage

1. Clone the repository and download the dataset from kaggle:

  Download data set from [Kaggle](https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing)
  
  
  ```bash
  git clone https://github.com/somwrks/Audio-Classifier.git
  cd Audio-Classifier
  ```

2. Install the required dependencies:
  
  ```bash
  pip install tensorflow tensorflow-io librosa matplotlib
  ```

3. Run the Jupyter Notebook main.ipynb to train the audio classifier and classify new audio files.

4. After running the notebook, the classification results will be saved in results.csv.

## Notes
  
  - The preprocess_mp3 function in the notebook is designed for WAV files. If using MP3 files, modify this function accordingly.
  
  - Monitor training/validation metrics during model training to ensure convergence.
  
  - Verify the contents of results.csv to ensure correct classification results are saved.

## License

  This project is licensed under the MIT License.
