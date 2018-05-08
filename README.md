# Modified NDVI

The NDVI is highly sensitive to zero or negative reflectance values which may appear after atmospheric correction even with a high quality atmospheric correction processor. 

Adding a small constant to the red surface reflectance solves the issue. This Jupyter Notebook shows what happens and how it is solved. 
