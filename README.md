# Face-Recognition-Attendance-Management-System
Attendance Management System based on Face Recognition using Python and OpenCV

### Sourcerer
<img src="https://avatars.githubusercontent.com/u/105853513?v=4" height="50px" width="50px" alt=""/>

### Code Requirements
- OpenCV(`pip install opencv-python`)
- Tkinter(Available in python)
- PIL (`pip install Pillow`)
- Pandas(`pip install pandas`)

### What steps you have to follow??
- Download my Repository 
- Create `TrainingImage` folder in a project.
- Open `AMS_Run.py` and change the all paths with your system path.
- Run `AMS_Run.py`.

### Project Structure

- After run the program you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your face and save the images in `TrainingImage` folder.
- After that we need to train a model(to train a model click on `Train Image` button).
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it will fill the attendance by scanning your face using its trained model (model will save in `TrainingImageLabel` )
- It will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to you in `AMS_Run.py`.
- `Manually Fill Attendance` Button in UI is to fill the attendance manually(without face recognition),it also creates a `.csv` file and stores it in the database.


### Notes
- It will require high processing power(more than 8gb).
- Noisy image can reduce the accuracy, so quality of images should be good.
