# Agrex.AI

Took subsections of the given image by cropping it into five small parts.
Performed data augmentation over those 5 cropped images and then annotated each one them on makesense.ai

Used the YOLOv5 model to train for a total of 100 epochs on the dataset created after augmentation.

# Final Result
![result](https://user-images.githubusercontent.com/104379823/215133361-5ddaa3c3-4675-4f2c-aba2-dc8a4b020b9b.jpg)

**It was able to detect a total of 101 transistors in the image, where the true count of the transistors is 100.
