# Object-Detection

This program uses Open CV library to detect objects in any image. It shows a bounded box and the probability of the class of the object detected.

It uses an algorithm known as Single Shot Detector (SSD) originally developed by Google and a neural network known as MobileNet, also developed by Google.

In this project, we use an already-trained model known as MobileNet SSD which is trained on the COCO dataset (Common Objects in Context). It can detect 20 objects in images including airplanes, bicycles, birds, boats, bottles, buses, cars, cats, chairs, cows, dining tables, dogs, horses, motorbikes, people, potted plants, sheep, sofas, trains, and tv monitors.

We provide the path to Caffe prototxt file, path to Caffe model, path to the image as arguments while running to the program.

For example, to detect objects on the image01.jpg file in the Images folder, the command to be run is:

```
python deep_learning_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel --image images/image01.jpg

```
## Input

<img width="601" alt="image" src="https://user-images.githubusercontent.com/55789995/159118813-8f4dbf21-0608-4bfb-93c0-1e02f71c46f5.jpg">

## Output

<img width="601" alt="image" src="https://user-images.githubusercontent.com/55789995/159118839-962926c9-b461-41d8-a734-a90ce16009f0.png">


