# Vehicle_Classification
Vehicle classification model training using tensorfow on google colab.
Developed a 7-class vehicle classification system using transfer learning with the pre-trained VGG16 architecture (without top layers).

Designed a custom image dataset comprising multiple vehicle types (car, truck, bike, bus, etc.); used OpenCV and PIL for data preprocessing, including resizing (128×128), normalization, and augmentation.

Added custom dense layers (128 → 64 → 7 softmax) on top of VGG16's convolutional base, followed by end-to-end model training.

Achieved 93.35% classification accuracy on the validation set after 9 epochs of training with categorical crossentropy loss and SGD optimizer.

Model compiled with accuracy as a key metric and evaluated using confusion matrices and learning curves.

Final model exported in .h5 format for further use in embedded/real-time applications.

Explored use cases such as automated toll booth systems, vehicle access control, and fleet categorization—relevant to large-scale retail/logistics environments like Schwarz Group.
