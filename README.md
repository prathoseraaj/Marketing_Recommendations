# Marketing-Recommendation-Engines

## Description
A Regression type prediction model using *Random Forest Classifier* algorithm. It uses MSE (Mean Squared Error) as the metric for prediction.

## Steps

### Building Files
1) train_model.py: which has regression model code
2) requirements.txt: which has the required library names
3) AEP_hourly.csv: .csv dataset which includes the data regarding counsumer forcast prediction
4) Dockerfile: which contains the commands to be run in docker

### Git & Other Commands used in Command Prompt
1) `mkdir <file_name>` to create the folder
2) `cd <file_name>` to go inside the folder
3) `git init`, initializing folder as git repository
4) manually add all the files
5) `git add .` to add all the files into git track
6) `git commit -m "<message>"`, it commits whatever is there in the track
7) `git remote add origin <GitHub repository link>`, builds connection between git and github
8) `git push --set-upstream origin master`, sends all the files from git to github.


### Jenkins
1) created a new item with item name as **<item_name>**
2) selected *Freestyle project* as the item type
3) selected *Git* in **Source Code Management**
4) added *Execute Windows batch command* step in **Build Steps**
5) Saved the Configurations
6) Clicked build now

#### Output
![Screenshot 2024-11-12 104248](https://github.com/user-attachments/assets/71a08a79-1d3c-4d4f-8a62-f35a9b25f814)


### Dockers
1) used `cd` to go forward and `cd..` to do backward, to get to the correct path in command prompt (i.e. the folder where all the files including docerfile is located.
2) executed the command `docker build -t <docker_image_name> .` to build the docker image.
3) executed the command `docker run <docker_image_name>` to run the docker image.

#### Output
  ##### Command Prompt
  ![Screenshot 2024-11-12 104308](https://github.com/user-attachments/assets/d32c95d3-761c-4594-a600-2934f5489ff4)

  ##### Docker Hub
![Screenshot 2024-11-12 104317](https://github.com/user-attachments/assets/f7b90b07-78bc-45a6-85d7-6e198f3e13fb)

Selenium


integrated flask into app.py. And build an html file called index.html inside templates folder.
created selenium_test.py file which contains the selenium code for autotesting app.py




![image](https://github.com/user-attachments/assets/9bf552cd-c914-401c-a1a9-468d7aea79f4)




