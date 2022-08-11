# Optic-disc-segmentation

Optic Disc Segmentation
-----------------------

Steps to run: 

- Please extract the archive folder and in it: 

|- ODS_Navyadhara
	|- Method_1
  	  |- ODS_Method-1.py
  	  |- ODS_Method-1.ipynb

	|- Method_2
	  |- ODS_Method-2.py
	  |- ODS_Method-2.ipynb
	  |- Mnet_Models
	  |- utils_Mnet.py
	  |- Model_DiscSeg.py
	  |- Model_MNet.py

After extracting, 

- for method-1, please perform the execution with the image data as working directory

```
python3 ODS_Method-1.py

```

- For method-2, please place the Mnet_Models folder along with the python files in to the data directory, then

```
python3 ODS_Method-2.py

```

The results obtained from each method are stored into folders created while execution.

Please use the Notebooks for simpler execution and visualisation. 




 

