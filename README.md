# LSTM-Stock-Price-Predictor
This repository contains a Jupyter notebook that uses an LSTM (Long Short Term Memory) model to predict the future stock prices of a company, using the company's historical stock prices.

## Features
- Utilizes LSTM, a type of Recurrent Neural Network (RNN), to predict stock prices.
- Utilizes Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and TensorFlow libraries in Python.
- Data visualization of real and predicted stock prices.
- The model is trained on historical data of Apple's stock prices.
- The model is saved and can be reused for future predictions.

## How to Use
1. Clone the repository.
2. Open the Jupyter notebook file (`stockprice_using_lstm.ipynb`).
3. Run all cells in the notebook.

Ensure you have all the necessary Python packages installed. You can do this by running `pip install -r requirements.txt` in your command line before running the Jupyter notebook. The `requirements.txt` file should list all the necessary Python packages.

## Data
The data used in this notebook is from `AAPL.csv`, which contains the historical stock prices for Apple Inc. 

## Model
The notebook contains the code to train an LSTM model on the stock prices. The model's architecture includes two LSTM layers and a Dense output layer. The model uses mean squared error as the loss function and Adam as the optimizer.

## Results
The notebook includes cells to plot the original and predicted stock prices for visual comparison.

## License
This project is licensed under the terms of the MIT license.

## Contributions
Contributions are welcome. Please create an issue to discuss the changes or improvements before making a pull request.

Please note that this project comes with a [Contributor Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/). By participating in this project, you agree to abide by its terms. 

If you have any questions or need further clarification, feel free to raise an issue.

**Remember:** Always replace the relevant parts in the README with your own specific information, such as how to install and run the project, any prerequisites, and additional steps to get the project running correctly.
