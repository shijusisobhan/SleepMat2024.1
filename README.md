# SleepMat2025.1 (9/26/2025)

We introduce *SleepMat*, a sleep analysis software developed in MATLAB with a user-friendly graphical user interface (GUI) to analyze *Drosophila* activity monitoring data. [Here you can find the publication.](https://academic.oup.com/sleep/advance-article/doi/10.1093/sleep/zsac195/6674229?searchresult=1)

This repository includes: A) A standalone application that does not require MATLAB to be installed (Windows). B) A p-code version that runs SleepMat within MATLAB, which requires a MATLAB license (Both Windows and Mac).

A well-documented user guide and a walkthrough example are also provided. For any inquiries, please contact the [Allada Lab, Michigan Neuroscience Institute, University of Michigan, Ann Arbor, MI 48109-2800 ](https://alladalab.org/)

Email: rallada@umich.edu


### Steps to run SleepMat in MATLAB
1.	Download the file _SleepMat_Require_Matlab.zip_
	
2.	Extract the file (_sleepmat.p_)

3.	Open Matlab.
   
4.	Change the current folder to the new folder where _sleepmat.p_ file is located. E.g., If _sleepmat.p_ file is saved in the 'D' drive, in a folder _SleepMat_Require_Matlab_ then to change the current folder, type the following line in the MATLAB command window:
   
	_cd D:\SleepMat_Require_Matlab_

5.	To open the software, type _sleepmat_ in the MATLAB command window, then hit enter.

   ### SleepMat standalone app installation on Windows

1.	Download the _SleepMat_standalone_app_Windows.exe_ file
   
2.	Double click on the _SleepMat_standalone_app_Windows.exe_ file.
	
3.	Please check the box for creating the shortcut to the Desktop.
   
4.	Depending on your machine and internet connection it will take 5-10 min to complete the installation. By default, SleepMat installed in the 'C:\Program Files' folder
   
5.	To run the SleepMat, double click on the _SleepMat_ icon on the desktop

### SleepMat standalone app installation on Mac (Coming soon...)

1.	Download the _SleepMat_standalone_app_Mac.app.zip_ file
   
2.	Extract the file
   
3.	Double click on the extracted file
   
4.	Follow the instruction on the pop up windows.
   
5.	Depending on your machine and internet connection it will take 5-10 min to complete the installation.
    
6.	To run the SleepMat, double click on the SleepMat icon

### New in 2025.1 (9/26/2025)

  ### Fixes & Improvements

1. Sleep Parameter Analysis Error

Issue: 30-minute intervals with more than 30 channels per board caused errors.

Fix: The update now properly calculates sleep parameters for intervals with >30 channels per board. Results have been validated.

2. Invalid Date Error with Missing Values & Single-Digit Day Format

Issue: Invalid date errors occurred when missing values were present and when using single-digit day formats (e.g., 3 Aug 24).

Fix: SleepMat now supports both 03 Aug 24 and 3 Aug 24, with or without missing values.
