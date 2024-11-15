README: Instructions for Running the Code


This repository contains the code for a machine learning project implemented in a Google Colab notebook. The dataset is stored in Google Drive, and you will need to mount your own Google Drive and provide the correct path to the dataset file in order to run the notebook.

Steps to Run the Code
1. Open the Google Colab Notebook
	•	Open the provided .ipynb file on Google Colab by clicking the link provided to the notebook.

2. Mount Your Google Drive
	•	The notebook contains a cell that will automatically mount your Google Drive. 
	•	After running the cell, you will be prompted to authenticate and provide access to your Google Drive.
	•	Click the link provided in the output, sign in to your Google account, and copy the authorization code back into the notebook to complete the mounting process.

3. Download and Upload the Dataset to Your Google Drive
	•	The dataset used in this notebook can be accessed using the link below. Please download the dataset and upload it to your Google Drive.(Download the folder ML Project dataset)  Dataset Link:
https://drive.google.com/drive/folders/1QwqNj8vgfYy1lMwOcMxdfQo1IWt11Ftj?usp=sharing
 If the link doesn't work , please copy and paste the Link into your web browser.	
•	Once downloaded, upload the dataset file to a folder in your Google Drive.

4. Change the Dataset Path in the Code
	•	After mounting your Google Drive and uploading the dataset to your desired folder, you need to update the file path in the notebook to point to the location of the dataset in your Google Drive.
	•	In the cell where the dataset is loaded (usually after the drive is mounted), change the path to the location where you saved the dataset in your Google Drive. For example:
	•	# Update the path to point to where you saved the dataset in your Google Drive
	•	dataset_path = '/content/drive/MyDrive/Datasets/dataset.csv'  # Change this to your dataset's path
	•	Adjust the file path according to where you saved the dataset in your Google Drive.

5. Run the Remaining Code
	•	Now that the dataset is loaded, you can run the remaining code in the notebook. This will process the data, perform clustering, and evaluate the model.
	•	All required steps for data preprocessing, training, clustering, and evaluation will be executed sequentially.

Package Requirements
Ensure the following Python packages are installed in your Google Colab environment:
	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn
	•	scikit-learn
These packages are required for data manipulation, clustering, visualization, and evaluation.


Notes
	•	Dataset: Make sure the dataset is downloaded and placed in the correct path in your Google Drive.
	•	Running the Notebook: The notebook is designed to be run cell by cell in the Colab environment, or it may cause the different models to overlap the variables.

Group 13: Richard David, Vishwanath Singh, Ishita Singh
