# M&M Image Classifier
This project can be used to recognize and predict whether the input image is Malayalam actor Mohanlal or Mammootty using Machine Learning. In this project we have built a CNN in Keras with Python. A web app can classify the given image as Mohanlal or Mammootty. 

#Team members
1.	Sania Maria Sabu
2.	Sandra Elizabeth Sabu
3.	Kaveri Menoki

#Team Id

BFH/recA6bskyiUmQgbxA/2021

#Link to product walkthrough
link to video

#Work Flow of the Product
1.	A CNN algorithm is created using tensorflow and keras libraries.
2.	The training and testing datasets are created using the images of Mohanlal and Mammootty from Kaggle dataset.
3.	A trained model created using the dataset is saved as '.h5' file format.
4.	A web app is created using flask API in backend and in the front-end, for UI, using HTML5, CSS and Javascript.
5.	The trained model is loaded in the web app backend.
6.	User can upload one image at a time to the web app, it is then saved into the folder named 'static'.
7.	Image is processed in the trained ML model and it will return the prediction as output whether the image is of Mohanlal or Mammootty. 

#How to Configure
Download the repository as zip. For downloading trained model click here.
Model Summary
![image](https://user-images.githubusercontent.com/45328455/119489560-71086480-bd79-11eb-9747-9106c43bc045.png)

 
#Installation
•	Fork & Clone the repo
       git clone https://github.com/[yourname]/BFH.git
•	Install all requirements
pip install -r requirements.txt
•	Run :
python3 app.py
•	Copy the localhost url (usually localhost:5000/) and paste in browser

#The databases in the system
   Static- This store the images send by users for prediction
   
#How to Run
1.	The downloaded file contains a app.py python file, also download the trained model from here.
2.	Open the python file and give the proper directory for importing the trained model. The HTML and CSS file (for UI) is present in the template folder.
3.	Open the terminal, select the directory and run the program.
4.	When it starts to run, the local IP will be present in the terminal. Search and open the IP in the browser and the webapp will start working from there.
5.	While starting the web app, you can see the file selection option. Click there, select and submit the image you want to predict.

![image](https://user-images.githubusercontent.com/45328455/119489670-8a111580-bd79-11eb-9dcd-692be48e4111.png)

6.	After submitting the image is processed and it predicts whether it is the image of Mammootty or Mohanlal.
![image](https://user-images.githubusercontent.com/45328455/119489754-a4e38a00-bd79-11eb-90ee-405feeddbd85.png)
![image](https://user-images.githubusercontent.com/45328455/119489772-ab720180-bd79-11eb-9ebe-7d1fec9cb0f2.png)

Note: This is a binary classification, so we can't get more than two result!

#File structure
| static
  | cast.h5
| templates  Contains all the html files

   | index.html
   | prediction.html
   | style.css
    .....
| Code.ipynb  Contains complete ML code for model training, testing and prediction
| README.md
| app.py : Contains all the python code    
| requirements.txt : contains the list of all dependencies to be installed



