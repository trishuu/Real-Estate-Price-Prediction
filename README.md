# Real-Estate-Price-Prediction
The Real Estate Price Prediction App uses machine learning algorithms to predict property prices based on key features like the number of bedrooms, bathrooms, and property size (in square feet).
It helps users — buyers, sellers, and real estate agents — estimate property values quickly and accurately.

# Features
* User-friendly Interface: Intuitive input fields for bedrooms, bathrooms, and size.
* Accurate Predictions: Estimates property prices using a pre-trained machine learning model.
* Real-time Feedback: Instantly displays the predicted price with a fun balloon animation.
* Scalable Model: Easily upgradable with new training data to improve accuracy.

# Technology Stack
* Streamlit: For building the interactive web app.
* Scikit-learn: For model training and prediction.
* Joblib: To save and load the model and scaler.
* Numpy: For data manipulation and preprocessing.

# How It Works

1. **User Inputs:**
   - Number of bedrooms
   - Number of bathrooms
   - Property size (in square feet)

2. **Data Preprocessing:**
   - Inputs are normalized using a pre-trained scaler to ensure consistency in scale and unit.

3. **Model Prediction:**
   - The machine learning model predicts the property price based on the normalized data.

4. **Real-time Display:**
   - The predicted price is displayed instantly on the app interface for the user to view.

5. **Interactive Feedback:**
   - A fun balloon animation appears when the prediction is made, making the user experience engaging.

# Applications

* Quick property evaluations for real estate agents to assist in pricing decisions.
* Instant price estimates for buyers and sellers to gauge market value.
* Market analysis and investment insights to help identify potential opportunities.
