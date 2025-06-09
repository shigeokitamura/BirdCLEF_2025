# BirdCLEF_2025
Acoustic Species Identification in the Middle Magdalena Valley
https://www.kaggle.com/competitions/birdclef-2025

## Description of the Project
* This project focuses on developing a machine learning model that identifies multiple species from audio recordings.

* The objective is to process continuous audio data and classify species based on their acoustic signatures.

* The project aims to contribute to ongoing conservation efforts in the Magdalena Valley by providing insights into biodiversity through passive acoustic monitoring.

## Problem Statement or Research Question
* How can machine learning models effectively identify bird, amphibian, mammal, and insect species from audio recordings   in the Middle Magdalena Valley of Colombia?

* Can we enhance model performance by incorporating data augmentation and transfer learning for underrepresented species?

## Data Sources
[BirdCLEF+ 2025 Competition Dataset](https://www.kaggle.com/competitions/birdclef-2025/data)

Data Structure:
* `train_audio/` : Training audio files for individual species.
* `train_soundscapes/` : Training soundscapes with multiple species.
* `test_soundscapes/` : Test soundscapes for evaluation.
/* `train.csv` : Metadata for training audio files (scientific_name, latitude, longitude, etc.).
* `taxonomy.csv` : Taxonomic information for species classification.
* `sample_submission.csv` : Example of the required submission format.

## Directory Structure
* `EfficientNet_B0/`
  * Starter notebooks with explanations to help you understand the starter notebook.
    * https://www.kaggle.com/code/kadircandrisolu/transforming-audio-to-mel-spec-birdclef-25
    * https://www.kaggle.com/code/kadircandrisolu/efficientnet-b0-pytorch-train-birdclef-25
    * https://www.kaggle.com/code/kadircandrisolu/efficientnet-b0-pytorch-inference-birdclef-25
* `KerasCV`
  * Last year's starter notebooks adjusted for this year
    * https://www.kaggle.com/code/awsaf49/birdclef24-kerascv-starter-train
    * https://www.kaggle.com/code/awsaf49/birdclef24-kerascv-starter-infer
* `transforming-audio-to-mel-spec.ipynb`
  * A notebook to convert birsong data to mel-spectrogram format
* `train.ipynb`
  * A notebook to build a model using EfficientNet V2.
* `inference.ipynb`
  * A notebook to create a csv file for submission
