# Crop Recommendation System

This **Crop Recommendation System** is a machine learning-based project aimed at providing farmers with the most suitable crop suggestions based on environmental and soil factors. The system uses various input parameters, such as nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall, to predict the ideal crop to cultivate in a specific region.

The model is trained using machine learning algorithms and is deployed using Flask to provide an easy-to-use web interface for making predictions.

---

## Features

- **Crop Prediction**: Based on user-provided parameters such as soil nutrients, temperature, humidity, and rainfall, the system recommends the best crop.
- **Web Interface**: A user-friendly web interface built using Flask for easy input and results display.
- **Model**: The prediction model is powered by machine learning algorithms like Decision Tree and Random Forest.

---

## Installation

### Prerequisites

Make sure you have **Python 3.x** installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/muralinp02/Crop-Recommendation-System.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Crop_Recommendation
   ```

3. Create a virtual environment:
   ```bash
   python -m venv myenv
   ```

4. Activate the virtual environment:
   - For Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - For macOS/Linux:
     ```bash
     source myenv/bin/activate
     ```

5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Run the application:
   ```bash
   python app.py
   ```

Your web app will be accessible at `http://127.0.0.1:5000/`.

---

## Usage

Once the application is running, navigate to the home page of the web application. Input the following parameters to receive crop recommendations:

- **Nitrogen (N)**
- **Phosphorus (P)**
- **Potassium (K)**
- **Temperature (Temp)**
- **Humidity**
- **pH**
- **Rainfall**

After submitting the form, the system will predict the best crop suited to your provided conditions.

---

## Models & Technologies Used

- **Machine Learning**: The crop recommendation model is built using machine learning algorithms like **DecisionTreeClassifier** and **RandomForestClassifier** from **scikit-learn**.
- **Flask**: A lightweight Python web framework for serving the prediction model.
- **Pickle**: Used for saving and loading the trained machine learning models and scalers.
- **HTML/CSS**: For creating the user interface.

---

## Contributing

Feel free to fork the repository and create a pull request for improvements. If you find any issues or bugs, please open an issue in the GitHub repository.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

