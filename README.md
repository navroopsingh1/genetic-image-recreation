# genetic-image-recreation
---

This application was the final course project for my **SFWRENG 2S03** - Principles of Programming course. We were tasked to create a **genetic algorithm** for the recreation of a given image starting from a randomaly generated PPM image. To further improve the accuracy of the produced image, an exponentially decaying adaptive learning rate was applied to the algorithm.

The program works by randomizing pixels and then using mutation and crossover to obtain an image closely resembling the inputted image. This is done by creating a population of randomized images using a pixel data structure, calculating the fitness score of each image and then ordering the images from highest to lowest fitness. Finally, the least fit 75% of the population images are then mutated, and the fitness is calculated again. This process is repeated until a close enough resembling image is reached.

### Sky and Water I
The Original image a long with the image recreated by the algorithm
### Original & Recreated Image
![Original](demo/me.png)
![Recreated](demo/me2.png)
### Gif of Image Recreation
![Demo Doccou alpha](demo/sample.gif)