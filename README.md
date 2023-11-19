# KMeansClustering
Overview
This Python code implements the K-Means clustering algorithm to segment an image into k distinct color clusters. The code uses the scikit-image library for image processing and matplotlib for visualization.
Prerequisites
Before running the code, ensure you have the following dependencies installed:
● numpy
● scikit-image ● matplotlib
You can install these dependencies using the following command:
pip install numpy scikit-image matplotlibpip install numpy scikit-image matplotlib
Running the Code
Update Image Path:
● Open the code file (kmeans_clustering.py) and locate the img_path
variable.
● Update the img_path variable with the file path to your input image.
Running on Jupyter Notebook:
● If you are running the code in a Jupyter Notebook, make sure to mount
your drive if the image is stored in Google Drive.
● Provide the correct file path after mounting the drive in the img_path variable.
Execute the Code:
● Run the script by executing the main() function at the end of the code.
Output:
● The code will display the original image and segmented images for
different values of k (2, 3, 6, and 10).
● Clustered images will be saved with filenames like
clustered_image_k2.png, clustered_image_k3.png, etc. Important Note
● Ensure that the input image path is correctly specified to avoid any file not found errors.
● The code uses predefined starting centroids, and the number of clusters (k) can be adjusted in the k_values list.
