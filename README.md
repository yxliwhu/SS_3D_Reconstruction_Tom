# SS_3D_Reconstruction_Tom
3D models generation with SS
# Usage
## Step1: Data Delete
When some user forget the colse the App when they finish the data collection, there are some data is not need for the data
processing. Please using [Tools](https://github.com/yxliwhu/SS_Data_Preprocessing) to process the data firstly. 
## Step2: Data Format Transformation 
### Open the software in **Release/ModelingFromRGB-D**
![software](images/1.png)
### Finish by the designed function 
 (**transtoTUMsets**)
![Tool](images/2.png)
The output data is stored in the directory **[Folder]\trans\SaveFile\TUMsets\**
![Dir](images/5.png)
## Step3: 3D Point Cloud Generation
### Import **configuration** file
Copy [configuration.txt](configuration.txt) to the data folder **[Folder]\trans\SaveFile\TUMsets\**
![Tool](images/4.png)
### Model generation
Using software funciton (**SLAMNew**) to finish this action
![Tool](images/3.png)
The point cloud will be stored in  **[Folder]\trans\SaveFile\TUMsets\porintcloudAll**
