# Building-a-Neural-Network-from-Scratch-for-Digit-Classification
This project demonstrates how to build, train, and evaluate a simple neural network from scratch (using only NumPy) for handwritten digit classification on the [MNIST dataset](https://www.openml.org/d/554). The code is implemented in a Jupyter Notebook and walks through every step, from data loading to prediction and visualization.

## 🚀 Features

- **No Deep Learning Libraries:** Neural network implemented using only NumPy.
- **Data Handling:** Loads and preprocesses the MNIST dataset using scikit-learn.
- **Network Architecture:** 
  - Input layer: 784 nodes (28x28 pixels)
  - Hidden layer: 128 nodes (ReLU activation)
  - Output layer: 10 nodes (Softmax activation)
- **Training:** Mini-batch gradient descent with forward and backward propagation.
- **Evaluation:** Computes accuracy on the test set.
- **Visualization:** Displays sample predictions with matplotlib.

## 📁 File Structure

- `mnist.ipynb` — Main Jupyter notebook containing all code and explanations.

## 📝 Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**
   ```sh
   pip install numpy scikit-learn matplotlib
   ```

3. **Run the notebook:**
   Open `mnist.ipynb` in Jupyter Notebook or VS Code and run all cells.

## 📊 Results

- Achieves over **93% accuracy** on the MNIST test set.
- Visualizes predictions for individual test images.

## 🧠 Key Concepts

- **One-hot encoding** for target labels
- **Parameter initialization** for weights and biases
- **Forward propagation** (ReLU, Softmax)
- **Loss calculation** (Cross-entropy)
- **Backward propagation** (manual gradients)
- **Parameter updates** (Gradient Descent)

## 📷 Example Output

![MNIST Sample Prediction](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

This project is licensed under the MIT License.

---

**Happy Learning!**
