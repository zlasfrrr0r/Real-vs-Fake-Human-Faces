# Real-vs-Fake-Human-Faces

## 📌 Subject ##
This project aims tackles the growing challenge of distinguishing real human faces from artificially generated ones, such as those produced by deepfake technologies and GANs. With the increasing accessibility of AI-generated media, verifying authenticity has become an urgent technical and ethical concern.
The model built here provides good accuracy (~87%) to distinguish between real and deepfaked human faces

## 📌 Objective ##
- Build a deep CNN with Dropout regularization to avoid overfitting.
- Use **EarlyStopping** for efficient training.
- Monitor both training and validation metrics and attempt to **diagnose overfitting**.

## 📂 Dataset
Dataset: RVF10K

7,000 training images

3,000 validation images

Labeled as real or fake

## 📊 Final Results

| Metric       | Value       |
|--------------|-------------|
| **Loss**     | 0.337       |
| **Accuracy** | ~87.9%      |

## 📎 Notes

- Decent accuracy given the available dataset.
- Need a larger dataset to achieve excellent accuracy.
