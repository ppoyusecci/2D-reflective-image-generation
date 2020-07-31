# 2D-reflective-image-generation

This is my FYP.

A machine learning model made with tensorflow
By FYP Tom, Aaron, Craig


Objectives

The goal of this project, as mentioned above, is to develop a method using Generative Adversarial Networks (GAN) to generate reflections from an image, i.e. create reflections on mirror-like virtual objects when they are added to a photo via photo editing apps. When we use the term reflection, we refer to a selection of phenomenon. Most obviously, we refer to clear reflections as seen in mirrors. Also included in this category are more dim reflections such as those from surfaces made of metals, glass, porcelain, waxed wood, and marble, to name a few. Additionally, we also refer to the diffusion of colour onto immediate surroundings. This phenomenon will be explained in greater detail during the Literature Review. A key goal in this project is to be able to produce these reflections in near real time. This feature is what gives our project an advantage over any similar research project.


During our project development, the following objectives will mark our progress:
1. Extract training and testing datasets.
2. Design and implement GAN.
3. Train the GAN and test the result of the generator for its speed and ability to generate realistic reflections consistently.
4. Find out the fastest and most realistic generator by testing out different GAN implementations.


To achieve the first goal, screenshots would be taken from game scenes that are rendered with reflections both disabled and enabled using the Unreal game engine. Screenshots without reflections would be fed to the GAN as inputs and the results would be compared with screenshots that had reflections enabled.
To achieve the second and third goal, TensorFlow backend would be used to leverage its rich API for building and testing GAN.
To achieve the fourth goal, the time taken by generators to create reflections would be compared with current available methods and an evaluation survey would be conducted to identify the system that generates the most realistic reflections.
The biggest challenge will be to extract the data, as no other research has been done in a similar field and there is currently no data archive to make use of. Designing the GAN will also be challenging for the same reason, meaning we will have to rely on the limited references available to generate reflections.
