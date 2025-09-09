Image Segmentation Project

This project provides a demonstration of several fundamental image segmentation techniques using Python and the OpenCV library. The code is structured as a single, self-contained script that applies different segmentation methods to a given image and displays the results.

The project is designed to be run in any Python environment where the required libraries are installed, including local machines or cloud platforms like Google Colab.

Features
This script demonstrates the following image segmentation methods:

Basic Global Thresholding: A simple, yet effective method for segmenting an image based on a single intensity value.

Sobel Edge Detection: Identifies the edges in an image by calculating the gradient magnitude, useful for finding object boundaries.

Region Growing: A segmentation method that groups pixels in an image into regions based on their intensity similarity to a "seed" point.

Region Splitting & Merging: An illustrative example of a quadtree-based segmentation approach that recursively splits regions and merges them back together based on a statistical measure (e.g., variance).

Prerequisites
To run this code, you need to have the following Python libraries installed:

opencv-python

numpy

matplotlib

You can install them using pip:

pip install opencv-python numpy matplotlib

Usage
Save the Code: Save the provided Python code as a file named image_segmentation.py.

Prepare an Image: Place the image you want to segment in the same directory as the script.

Update the Path: In the image_segmentation.py file, change the image path in the process_and_display function call to match your image file name.

# Replace 'image1.webp' with the name of your uploaded image file.
process_and_display('your_image_name.jpg')

Run the Script: Open a terminal or command prompt, navigate to the directory where you saved the files, and run the script with the following command:

python image_segmentation.py

The script will generate a series of plots, each showing the original image alongside the result of a different segmentation method.
