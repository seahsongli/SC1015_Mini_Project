# SC1015_Mini_Project - Formula 1 Top 3 Predictor for Qualifying Races
---

## Project Overview
This project aims to develop a predictive model for identifying the top 3 drivers in Formula 1 races. Leveraging machine learning techniques and data analysis, we explore patterns and trends in historical Formula 1 data to predict the top performers in qualifying races.

## Background
Formula 1 (F1) is the pinnacle of international open-wheel auto racing, known for its high-speed races and competitive teams. Drivers compete in a series of Grand Prix events across the globe, with results contributing to championship standings. The performance in qualifying races determines the starting grid for the main races, making it a crucial aspect of each event. Understanding the factors that influence success in these races can provide valuable insights for teams, analysts, and fans alike.

## Features
### Data Preprocessing
- **Handling Missing Values**: Techniques to detect and manage missing data through imputation or removal.
- **Encoding Categorical Features**: Converting categorical data to numerical format (e.g., one-hot encoding).

### Exploratory Data Analysis (EDA)
- **Data Visualization**: Charts and graphs to understand relationships, distributions, and trends.

### Machine Learning Algorithms
- **Model Implementation**: Using Random Forest & Neural Networks to predict the top 3 qualifiers in Formula 1 races.
- **Hyperparameter Tuning**: Adjusting model parameters for optimal performance.

### Upsampling Techniques
- **Addressing Class Imbalance**: Applying SMOTE (Synthetic Minority Over-sampling Technique) to balance class distribution.

### Model Evaluation
- **Performance Metrics**: Evaluating model accuracy, precision, recall, and F1-score.

## Installation
To run this project locally, follow these steps:
1. Clone the repository: `git clone git@github.com:seahsongli/SC1015_Mini_Project.git`
2. Navigate to the project directory: `cd SC1015_Mini_Project`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage
1. Prepare your Formula 1 dataset in CSV format.
2. Run the Jupyter Notebook `Formula1_Top3_Predictor.ipynb` to execute the code cells and train the predictive model.
3. Analyze the model performance and evaluate the results using the provided metrics.


## Project Structure
- **Race_Results && Season_Calenders**: Contains the dataset(s) used for training and testing the model.
- **Formula1_Top3_Predictor.ipynb/**: Jupyter Notebooks with code for data preprocessing, EDA, and model training. Also contains outputs and results from model evaluations.


## Contributing
Contributions to this project are welcome! If you'd like to contribute, please follow these steps:
1. **Fork the repository** and create a new branch for your feature or bug fix.
2. **Submit a pull request** with a description of your changes.
3. **Ensure code quality** by running any provided tests and following code style guidelines.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
We would like to thank the Formula 1 community for providing data and insights that made this project possible. Special thanks to our teaching assistants and instructors for their guidance and support.