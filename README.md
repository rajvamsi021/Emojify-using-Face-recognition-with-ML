# Emojify-using-Face-recognition-with-ML
Turn your facial expression into an emoji.
# What I did here
1) Decided what emojis to use.
2) Used FER 2013 Dataset.
3) Trained a CNN on these images.
4) As of today there are 7 facial expressions .

# Facial expressions used
0 Neutral
1 - Smile/Happy
2 - Sad
3 - Wink
4 - Kiss
5 - Surprised
6 - Angry

# About the Project
Developed using keras framework. In this Project first detect the user face using OpenCV and Cascadeclassifier. After that it will detect the human expression like angry, sad, happy etc, and after the this save model will used for tkinter GUI it will send expression wise emotion into another frame.

# Comparison between train and test datasets

1) Plot between train_loss and test_loss:-

![WhatsApp Image 2021-04-08 at 12 22 57 PM](https://user-images.githubusercontent.com/69450197/118387642-2da54c00-b63d-11eb-8b42-2a6468393b5a.jpeg)

2) Plot between train_accuracy and test_accuracy:-

![WhatsApp Image 2021-04-08 at 12 27 13 PM](https://user-images.githubusercontent.com/69450197/118387717-a0aec280-b63d-11eb-89e4-66fbf81da78f.jpeg)

