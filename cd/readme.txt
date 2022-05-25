PROCESS :
•	In this project we build a Web Application powered by Azure  Linux  instance 
        to display predicted results from the SQL Database.
•	The input is image dataset. The data is collected manually from external sources
         and it is used for  analysis.
•	The input image data  sets are converted to gray scale image and further Segmentation
         and  Morphological filtering is performed on image data using python image  processing.
•	The processed image is converted to a dataset after applying Clustering  and Ranking Algorithms.
•	The extracted dataset is passed to a model trained using  Convolutional neural network (CNN) with increasing EPOCH. 
•	The model is  trained with the help of pre-trained data stored in Key-Value pairs in MongoDB.
•	Once the prediction is done the predicted values are stored in LSTM for future and  fast processing.
•	Cancer stage identification is done with the help of Ranking results  and is
        updated in MySQL Database for backend services like Flask to fetch and  propagate in user interface portals. 
•	Performance of the system is increased with  encouraging results of initial experiments. 
•	So, the data collected initially data undergoes image processing and helps us 
        identify the  presence of cancer cells and briefly displays the predicted result. 
        This predicted  result is shown to the pathologists for further treatment of colorectal cancer. 
•	The ultimate goal of this project is that  an automated solution could potentially reduce 
        the workload of pathologists by  acting as a screening device and may reduce the subjectivity in diagnosis. 

STEPS TO EXECUTE THE PROJECT :
1.	Send the zip file 
2.	Install python3
3.	Run python3 -m pip install pipenv
4.	Run python3 -m pipenv install
5.	Run python3 -m pipenv shell
6.	Run flask Run
7.	Navigate to the url you get in the command prompt
Then,
1.	Navigate to the folder where project is implemented 
2.	Type pipenv shell
3.	Type flask run
