# linear-regression-profit-forecast
It's a project that uses linear regression to predict profits from ice cream sales. This model is trained based on factors such as the weather to help companies in the ice cream sector better understand their future revenue and make informed decisions.

## Getting Started

### Steps in the Notebook

### 1. Importing Libraries

The project uses the following libraries:

- TensorFlow 2.x
- Pandas
- NumPy
- Seaborn
- Matplotlib

### 2. Importing the Dataset

The dataset used in this project contains two columns:

- **Temperature**: The temperature for each day.
- **Profit**: The daily profit for the ice cream business.

### 3. Data Exploration

- **Visualization**: Seaborn and Matplotlib are used to create plots that visualize the relationship between temperature and revenue.

### 4. Model Training

- **TensorFlow**: A neural network model is built using TensorFlow to predict profit based on temperature.
- The model architecture includes:
  - Dense layers
  - Mean squared error as the loss function
  - Adam optimizer

### 5. Model Evaluation

The model is evaluated using standard metrics such as Mean Squared Error (MSE) to determine how well it predicts profits.

## Contributors

- [Vinicius Frois](github.com/vmfrois)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
