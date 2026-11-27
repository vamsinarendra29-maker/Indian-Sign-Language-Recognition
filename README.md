# Indian Sign Language Recognition Using Deep Learning

## Project Overview
An AI-based alphabet gesture recognition system using CNN and MobileNetV2 transfer learning.

## Project Objectives
- Recognize 24 alphabet gesture classes.
- Perform image preprocessing and augmentation.
- Compare CNN and MobileNetV2 models.
- Develop a Streamlit prediction interface.

## Dataset
- Total images: 4,971
- Training images: 3,468
- Validation images: 736
- Testing images: 767
- Gesture classes: 24

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit

## Model Comparison

| Model | Validation Accuracy |
|---|---:|
| Baseline CNN | 30.84% |
| MobileNetV2 | 99.46% |

## Final Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 94.65% |
| Macro Precision | 95.02% |
| Macro Recall | 94.06% |
| Macro F1-Score | 94.00% |
| Correct Predictions | 726 |
| Incorrect Predictions | 41 |

## Run the Application

Install dependencies:

`pip install -r requirements.txt`

Launch Streamlit:

`streamlit run app.py`

## Limitations
- Supports only 24 trained alphabet gestures.
- External image performance remains unverified.
- Continuous sign language translation is not supported.

## Future Enhancements
- Real-time webcam recognition.
- Hand landmark detection using MediaPipe.
- Expanded dataset and independent signer validation.
- Text-to-speech integration.

## Conclusion
MobileNetV2 demonstrated strong performance on the provided test dataset, achieving 94.65% accuracy.

## Project Information
- Project Type: AI Capstone Project
- Project Code: PRAICP-1000-IndiSignLang
- Domain: Artificial Intelligence and Computer Vision
