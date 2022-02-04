# Facemask_Detection

Before getting started, let us understand the problem better. We want to build a system that can detect faces in real-world videos and identify if the detected faces are wearing 
masks or not. So, what do we mean by real-world videos?

If you look at the people in videos captured by CCTV cameras, you can see that the faces are small, blurry, and low resolution. People are not looking straight to the camera, and 
the face angles vary from time to time. These real-world videos are entirely different from the videos captured by webcams or selfie cameras, making the face mask detection 
problem much more difficult in practice.

In this blog post, we will first explore mask/ no mask classification in webcam videos, and next, shift to the mask/ no mask classification problem in real-world videos as our 
final goal. Our reported model can detect faces and classify masked faces from unmasked ones in webcam videos as well as real-world videos where the faces are small and blurry and 
people are wearing masks in different shapes and colors. We will explain more details about the face detector in the next part.

# Model

![image](https://user-images.githubusercontent.com/86097201/152500972-0b9b9ad4-7b32-48f8-a2fd-f4ce244fba53.png)

# Dataset

![image](https://user-images.githubusercontent.com/86097201/152501029-4dbb5d82-c2f8-4436-b6e8-055b0bd43003.png)
