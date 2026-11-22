# Brain Tumor Classification Using Convolutional Neural Networks (CNN)

An academic deep-learning project that classifies brain MRI images into four categories:
- Glioma
- Meningioma
- Pituitary tumor
- No tumor

**Authors:** Sujith Ram V and Nithyasree N

## Project overview

The notebook builds a Sequential CNN using TensorFlow/Keras. MRI images are resized to
128 × 128 pixels, normalized to the 0–1 range, and processed in batches of 32. The model
uses convolutional and max-pooling layers, a dense layer, dropout, and a four-class softmax
output.

## Reported results

- Training accuracy: 99.33%
- Validation accuracy: 93.57%
- Test accuracy: 89.81%

The report describes stronger classification performance for the No Tumor and Pituitary
classes, with some confusion between Glioma and Meningioma.

## Repository contents

- `Brain_tumor_classification.ipynb` — model development, training, evaluation, and sample predictions.
- `docs/Project_Report.pdf` — project report.
- `docs/Project_Presentation.pptx` — project presentation.

## Dataset

The project uses a Brain Tumor MRI Dataset obtained from Kaggle. The dataset is not included
in this repository. Download the dataset separately and arrange it with `Training` and
`Testing` folders, each containing the four class subfolders expected by the notebook.

The notebook was originally prepared for Google Colab and includes Google Drive mounting
and a dataset ZIP path. Update those paths to match your own Colab/Drive setup before
running it.

## Environment

Install the dependencies listed in `requirements.txt`. TensorFlow compatibility can depend
on your Python version and operating system; Google Colab is a convenient environment
for running this notebook.

## Important note

This is an academic machine-learning project for learning and demonstration. It is not a
medical device and must not be used to diagnose, rule out, or guide treatment for brain
tumors. Clinical decisions must be made by qualified healthcare professionals.
