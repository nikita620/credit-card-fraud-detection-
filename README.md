# Credit Card Fraud Detection

![Credit Card Fraud Detection](path/to/your/image1.png)

This project aims to detect fraudulent credit card transactions using ensemble methods such as AdaBoost and majority voting. 

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Models](#models)
- [Results](#results)
- [Acknowledgements](#acknowledgements)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Credit card fraud is a serious issue in financial transactions. This project leverages ensemble learning techniques, specifically AdaBoost and majority voting, to build robust fraud detection models. 

![Ensemble Methods](path/to/your/image2.png)

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```
2. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Preprocess the data:
    ```sh
    python preprocess.py
    ```
2. Train the models:
    ```sh
    python train_model.py
    ```
3. Evaluate the models:
    ```sh
    python evaluate_model.py
    ```

## Datasets
The dataset used in this project is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). Make sure to download and place the dataset in the `data` directory.

## Models
1. **AdaBoost**: This model uses the AdaBoost algorithm to improve the performance of the base classifier.
2. **Majority Voting**: This model combines multiple classifiers to make a final prediction based on the majority vote.

## Results
The AdaBoost model achieved an accuracy of **99.2%**, while the Majority Voting model achieved an accuracy of **98.9%**.

![Results](path/to/your/results_image.png)

## Acknowledgements
- The dataset was provided by [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Contributing
Contributions are always welcome! Please fork the repository and create a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

