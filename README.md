# photo manager with OpenCV

The application can do the following:

 Reads a path to an image folder as a command line argument.
 Reads all image files in .jpeg or .png format from the given folder.
 Combines the images into an image, the so called texture atlas.
 Saves the texture atlas in .jpeg or .png format to the working directory of the application.
 Creates the atlas metadata which for each image in the atlas includes the name, x axis coordinate, y axis coordinate, width, and height of the image.
 Saves the metadata as a text file in the working directory of the application.

The application uses opencv and filesystem library to manage images and read directory. Please read the PDF document for more information.
