# Detecting-pneumonia-from-chest-X-ray
##  About Dataset
The Dataset is downloaded from Kaggle. Link:https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

### CNN Model
Image size:64x64,
Batch_size=64,
Epochs:15,
Training accuracy:95.7%(approx),
Test accuracy:78.3%(approx).
### Vgg16 model
Image size:224x224,
Batch_size=128,
Epochs:10,
Training accuracy:94.17%(approx),
Test accuracy:79.12%(approx).
### ResNet152 model
Image size:224x224,
Batch_size=64,
Epochs:16,
Training accuracy:95.89%(approx),
Test accuracy:80.7%(approx).
# ResNet152 model:
it is used to Draw Class Activation Maps.
ResNet152 have a very deep network of up to 152 layers by learning the residual representation functions instead of learning the signal representation directly.
ResNet introduces skip connection (or shortcut connection) to fit the input from the previous layer to the next layer without any modification of the input.

