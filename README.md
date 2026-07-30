# HECA for Tomato Leaf Disease Classification

## Overview
Implementation and evaluation of Research based HECA, CBAM, Channel Attention, and Spatial Attention modules on MobileNetV3 for tomato leaf disease classification.

HECA achieved the best performance among all evaluated models, with a Macro F1-score of 0.95 and a Weighted F1-score of 0.96.

## Dataset
Tomato Leaf Disease Dataset
15,209 images
10 classes
## Dataset Link:
https://www.kaggle.com/datasets/yusufmurtaza01/tomato-leaf-disease

## Results

| Model | Accuracy |
|---------|---------|
| MobileNetV3 | 89.38% |
| MobileNetV3 + SA | 89.61% |
| MobileNetV3 + CA | 92.34% |
| MobileNetV3 + CBAM | 92.90% |
| HECA | 95.96% |

## Additional Evaluiation Logs and Note Book Link:
Model Logs: https://www.kaggle.com/models/redheadcoffee/heca-attention-models
  
Kaggle Notebook: https://www.kaggle.com/code/redheadcoffee/heca-accuracy-and-loss-and-roc-curves
