# RAID-database: Human responses to affine iage distortions

This repository contents the data and code to use the dataset described in the paper:
RAID-database: Human responses to affine image distortions

## Data
- *Raw data*: are the data collected in the experiments from the human observers following the description in the paper. 

- *MLDS data*: are the data that contain the computed MLDS responses. This data has been obtained by processing the *raw data* using the MLDS method. 

- *MOS data*: are the data adapted to be expressed in mean opinion scores (MOS). These data was obtained by aligning the MLDS responses in our experiments with the MOS in the TID2008 database. This alignment allows to use our database together with classical image quality databases. 

- Images: 
  
## Use examples

- How to load the databases:
https://colab.research.google.com/github/paudauo/BBDD_Affine_Transformations/Load_DDBB_example.ipynb

- How to load the raw data and compute the MLDS curve:
https://colab.research.google.com/github/paudauo/BBDD_Affine_Transformations/Load_MLDS_data_and_plot_curves.ipynb

- How to load the precomputed MLDS curves and plot them:
https://colab.research.google.com/github/paudauo/BBDD_Affine_Transformations/Load_DDBB_example.ipynb

- How to convert RAID responses to MOS:
https://colab.research.google.com/github/paudauo/BBDD_Affine_Transformations/Convert_MLDS_to_MOS.ipynb

- How to plot the relationship between the stimulus degree of distortion and the reaction time (RT):
https://colab.research.google.com/github/paudauo/BBDD_Affine_Transformations/Load_RAW_data_and_plot_left_right_RT.ipynb
  
