### Galactic Rotation Curves - DESI  
#### Project description  
Using neutral hydrogen detections from the ALFALFA survey and HI-MaNGA project, I will extend our data on the rotation of the MaNGA galaxies beyond their luminous, i.e. visible, extent. This will expand the work done by my advisor Kelly A. Douglass et al., who only measured the rotations out to the visible edge of the galaxies.  Because the density of the dark matter halo increases with radius, since it has to offset the decrease in the density of the visible matter to keep the rotation speed same, this initial study was limited to calculating a lower limit on the dark matter halo mass.  By extending the rotation curves with the neutral hydrogen measurements, my work will be to calculate a more accurate dark matter halo mass and better understand the influence of the void environment on a galaxy’s dark matter content.  
#### Changelog  
Research_2020.ipynb: Main file
velocity_distribution.ipynb: Using histograms to visualize the distribution of all possible WF50, WP50, WP20 rotational velocities
velocity_comparison.ipynb: Using scatter plots to understand how the velocities compare to each other for both GBT and ALFALFA data and choose a velocity to use for the rest of the analysis 
wf50_MHI_MStar_scatter.ipynb: Using a larger MaNGA file to add MStar columns to GBT and ALFALFA data sets. Find the relationship between WF50 and MHI / WF50 and MStar
Nearest_neighbor.ipynb: Finding the nearest neighbor in the kias7 data relative to the GBT and ALFALFA data sets (the combination of the GBT and ALFALFA set is named manga_HI) using KDTree
