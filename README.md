# Urban-point-cloud-classification
Point Cloud is a cloud of 3D points representing a particular object,Scene,etc.

This is a research Project which Focuses on classifying the respective points to its respective object cloud.There are 2 methods of doing this namely-
1.Segmentation classification
2.point by point classification

This project basically focuses on point by point classification.

The libraries needed for the processing are-

1.PyntCloud-https://github.com/daavoo/pyntcloud


2.Numpy


3.Pandas


4.Sklearn


5.Matplotlib.pyplot


6.Anaconda and Jupyuter Notebook


7.Open3D


Dataset Used-Paris Rue Madam Dataset(http://cmm.ensmp.fr/~serna/rueMadameDataset.html)
The algorithms used for classification in the basic model-Random Forests

Note:The Better library and Documentation for Point Cloud manipulation in Python is PCL-Python binding(https://github.com/strawlab/python-pcl).If C++ then the PCL library will be the best.

The PreProcessing Steps done For the Prilimnary Project is-

1.Voxel Grid Downsampling or Filtering

The Feature Extraction From the point Cloud is-

1.Eigen Values


2.Anisotrophy


3.Curvature


4.EigenTrophy


5.EigenSum


6.Linearity


7.Omnivariance


8.Planarity


9.Spehericity



The further Feature extraction that can be included in the further models are-

1.Slope


2.Height horizontal and vertical


3.Angular Features


4.Moments Calculation 

The post Processing techniques which can be used is-

1.Shape Distribution histogram

2.Graph cuts

This model gives an accuracy of 92% which can be improved by feature tuning and the above stated methods
