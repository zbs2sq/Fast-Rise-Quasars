# Fast-Rise-Quasars

## Jupyter Notebooks

### combineObservations
The first is combineObservations.
This notebook is intended to combine completed .csv files, weighted by their SNR. 
It is as simple as inputting your file locations when prompted, and it should do the rest.

### compareSpectrum
The second walks through the process of combining all MODS data together.
This code assumes a fairly strict layout of your file structure.
An example of this file structure is shown in "ExampleObjectFile".
There will be numerous other files that are created as you reduce your data, but your structure and naming conventions at the end should be as shown here to ensure a smooth run of 'compareSpectrum.'
You will also need accurate absolute fluxes in 'FinalDataFluxes.csv' in order for the program to know what the final flux should be to correct for it.
You will need the corresponding SDSS spectrum in the "Final Spectra" subfolder to compare to the Sloan data.
Running this whole program for each 'currentObject' as defined by the user in the second cell will produce an absolute flux calibrated spectrum.

## PDF Files
There are three .pdf files in this repository. 
Two of these are "MODs Reduction How-To" files, which document the process of reducing quasar data from the LBT MODs spectrograph. 
The file by Katherine is the primary one to follow.
The file by me should be consulted in parallel.

The Quasar Data pdf outlines much of the data of each object within this repository.
Data within this file includes:
 - RA
 - Dec
 - Redshift z
 - Which surveys it is from
 - R- or G-Band magnitude
 - Respective flux
 - SDSS Observation Date
 - Airmass (for some files)
 - Comments

This should provide an understanding of each object and its respective data.

## CSV Files
