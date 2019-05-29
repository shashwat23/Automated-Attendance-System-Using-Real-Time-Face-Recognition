# Automated-Attendance-System-Using-Real-Time-Face-Recognition
The project uses real time face recognition to update attendance. The algorithms used are Haar Cascade(Voila and jones) for object detection and LBPH for face recognition. The language used is python and several modules of it like tkinter, OpenCV, MysqlDB etc.
Steps to run the project:
1.Create a database(mysql) named Attendance
2.Create a table in named as login in Attendance database
3.Check the code to match the password for the database (check Gui.py login() function)
4.Run Gui.py
5.If first time user click on submit details fill the details and click on take image
6.After taking the the image copy them to TrainingImage folder and click on Train Image
7.Click on Quit
8.Now to mark the attendance clik on submit attendance face the camera and when your face in recognised press "q"
9.After Pressing "q" we can see our ID,Name,Date and Time in the terminal and a csv file in the folder named as "Attendance_(current date)_(current time)

Requirements
1. Python 3.5 and above
2.mysql
3.Opencv and opencv contrib
