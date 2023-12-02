# Sinewave Generator Example
This notebook implements a model that accepts a floating point number between 0 and 2Pi and approximates a sine wave (outputs the corresponding sine value between -1 and 1). This example is designed to demonstrate the basics of creating and training a TensorFlow (TF) Keras machine learning (ML) model, converting this model into a TF Lite model, and finally converting the TF Lite model into a C byte array for further deployment onto an embedded resource-restricted hardware system (like a microcontroller, MCU).

# Files
* tflite_sinewave_training.ipynb - a Google Collab notebook (1) implementing and training the TF model, (2) converting the TF model into a TF Lite model, (3) converting the TF Lite model into a C byte array, and (4) documenting various intermediate stages and results
* sine_model.tflite - the TFLite model
* sine_model.h - the tiny ML model converted into a C byte array 

# Acknowledgements/References
This project is based on the "Intro to TinyML Part 1: Training a Neural Network for Arduino in TensorFlow | Digi-Key Electronics" tutorial (URL: https://www.youtube.com/watch?v=BzzqYNYOcWc) [Last accessed on: November 30, 2023]