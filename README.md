# OcclusionSpectrum
The Occlusion Spectrum for Volume Classification and Visualization, as mutil-dimensional transfer function

Despite the ever-growing improvements on graphics processing units and computational power, classifying 3D volume data remains a challenge. In this paper, we present a new method for classifying volume data based on the ambient occlusion of voxels. This information stems from the observation that most volumes of a certain type, e.g., CT, MRI or flow simulation, contain occlusion patterns that reveal the spatial structure of their materials or features. Furthermore, these patterns appear to emerge consistently for different data sets of the same type. We call this collection of patterns the occlusion spectrum of a dataset. We show that using this occlusion spectrum leads to better two-dimensional transfer functions that can help classify complex data sets in terms of the spatial relationships among features. In general, the ambient occlusion of a voxel can be interpreted as a weighted average of the intensities in a spherical neighborhood around the voxel. Different weighting schemes determine the ability to separate structures of interest in the occlusion spectrum. We present a general methodology for finding such a weighting. We show results of our approach in 3D imaging for different applications, including brain and breast tumor detection and the visualization of turbulent flow.

http://ieeexplore.ieee.org/ieee_pilot/articles/06/ttg2009061465/article.html

http://vis.cs.ucdavis.edu/papers/correa_ma_occlusion_spectrum.pdf

http://www.paraview.org/Wiki/VTK/Occlusion_Spectrum#vtkImageOcclusionSpectrum_filter

