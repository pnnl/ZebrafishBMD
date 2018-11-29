<img src="/images/ZebrafishBMD.png" alt="ZebrafishBMD" width="150" height ="100" />

# ZebrafishBMD: A software program for benchmark dose calculations using toxicity screening data from high-throughput zebrafish assays 


The ZebrafishBMD program was written by Dr. Dennis Thomas and 
Dr. Harish Shankaran in collaboration with Dr. Katrina Waters, 
at the Pacific Northwest National Laboratory. 
The program was developed as part of projects funded by the National 
Institutes of Health and the Environmental Protection Agency.

## Main Features

The program calculates BMD10 values for 
22 developmental and 2 behavioral endpoints of zebrafish using the methods described
in the [paper]().

## Version

The current version (ZebrafishBMD v1.0) is a Windows 
standalone application that was created using Matlab 2016b. 
 
### Software requirements:
Matlab Runtime v. 9.1 (Matlab 2016b) for Windows

### Downloading and Running ZebrafishBMD

1. Download and unzip the following .zip folder files

	* `ZebrafishBMD_v1.0.zip`
	* `example_data_v1.0.zip`


2. Move the `input_data` folder from `example_data_v1.0` into `ZebrafishBMD_v1.0` folder

	The `input_data` folder contains zebrafish developmental and behavioral assay 
	data for 10 chemicals. Details about the assay and computational approach are 
	provided in this [paper]().
	
3. Go to `ZebrafishBMD_v1.0` folder on Windows command prompt window
4. Type `ZebrafishBMD.exe` and press Enter.
	A user interface window will open. The text fields are pre-filled, so the users don't
	have to edit these fields. Simple click on the 'Run' button at each step after the 
	previous step run is completed.
	
	

5. The program will create the following folders to save the run output files:

	* morphology_response_data
	* morphology_fit_results
	* behavior_response_data
	* behavior_fit_results

## Citing ZebrafishBMD

Please cite

```
Thomas, D. G., Shankaran, H., Truong, L., Tanguay, R. L., & Waters, K. M. (2018). Time-dependent behavioral data from zebrafish reveals novel signatures of chemical toxicity using point of departure analysis. Computational Toxicology. https://doi.org/10.1016/j.comtox.2018.11.001

```
## Disclaimer
This material was prepared as an account of work sponsored by an agency of the
United States Government.  Neither the United States Government nor the United
States Department of Energy, nor Battelle, nor any of their employees, nor any
jurisdiction or organization that has cooperated in the development of these
materials, makes any warranty, express or implied, or assumes any legal
liability or responsibility for the accuracy, completeness, or usefulness or
any information, apparatus, product, software, or process disclosed, or
represents that its use would not infringe privately owned rights.

Reference herein to any specific commercial product, process, or service by
trade name, trademark, manufacturer, or otherwise does not necessarily
constitute or imply its endorsement, recommendation, or favoring by the United
States Government or any agency thereof, or Battelle Memorial Institute. The
views and opinions of authors expressed herein do not necessarily state or
reflect those of the United States Government or any agency thereof.

		 PACIFIC NORTHWEST NATIONAL LABORATORY
			      operated by
				BATTELLE
				for the
		   UNITED STATES DEPARTMENT OF ENERGY
		    under Contract DE-AC05-76RL01830

