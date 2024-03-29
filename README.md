# Iranian Vehicle images dataset
### The dataset presented in this article contains 3000 images downloaded from online Iranian car sales companies, including Divar and Bama sites (" www.Divar.ir " ," www.bama.ir " ), which are manually labeled in three classes: car, truck, and bus.

Figure below are examples of the output of the algorithm for test images after training the YOLO network with this dataset : 

<p align="center">
        <img src="https://user-images.githubusercontent.com/61584820/181746019-c355ec70-507c-4c16-ac76-7bb9fed15acb.png" width=70% height=70%>
        <img src="https://user-images.githubusercontent.com/61584820/181745731-4340de84-8b6f-49ee-b4e7-5fc102cc576f.jpg" width=70% height=70%>
        <img src="https://user-images.githubusercontent.com/61584820/181746362-f280e651-1701-477b-bff2-d7717f9ddff4.png" width=70% height=70%>
</p>

------------------------------------------------------------------

## download Dataset
There are two ways to download the dataset :
1- Download from Roboflow :
2- Download as a zip file from this address :

| number | method | addres |
| - | - | - |
| 1 | Download from Roboflow <br>  |[addresroboflow](https://universe.roboflow.com/sipo/iranian-vehicle-cjfc5)
| 2 | Images with dimensions of 416 x 416 as a zip file in this Github  <br>  |[Iranian_vehicle_dataset.zip](/Iranian_vehicle_dataset.zip/)

 To train our detector we take the following steps:

------------------------------------------------------------------
## Dataset specifications
The total number of images in the dataset is 3000, which includes 5,765 labels of all classes. The average size of the dataset images is 0.36 mega pixels and the average dimensions of the images are 600 x 600 pixels .
<p align="center">
        <img src="https://user-images.githubusercontent.com/61584820/181755020-5157db78-fe2c-469a-882e-82b63df3aa7b.png" width=70% height=70%>
</p>



| :) | class name |  number of annotation  |
| - | - | - |
| 1 | car <br>  |4333   
| 2 | bus <br>  |893
| 2 | Truck <br>  |539



# license
1. This dataset is made available for academic use only. 
2. If you find your vehicle or personal information in this dataset, please contact us and we will remove the corresponding information from our dataset.
3. may not use this work for commercial purposes (for commercial use, please contact us)
4. If you use this dataset in your research , you should tag this GitHub and our article that will be published soon.
