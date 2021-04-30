# Maze-Solver
Python Application that solves mazes by the use of Dijkstra's algorithm

Given a maze as an image with a start and end point, this application will find the shortest path to solve the maze.

Each image is a 2D matrix of pixels of a particular size that depends on its resolution. Each pixel has a color which is given by its Red, Green and Blue (RGB) values.

Given an image, we will view it as a graph where each pixel of the image is a vertex and edges connect a pixel to its neighbor. The weight of an edge should be very small if the pixel colors are similar (i.e, the differences between r, g and b values are close to zero) and correspondingly large as the pixel colors diverge.

Given a source pixel  (𝑖0,𝑗0)  and destination pixel,  (𝑖1,𝑗1) , we wish find the shortest weight path from source to destination.

We will use opencv library, a popular computer vision library to load, and manipulate images of mazes.
