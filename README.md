Code powering the FaceTag system.

## Libraries Used

### facial recognition
1. Azure Face API module - for better and easy face recognition
2. OpenCV
3. Flask server
4. Python

### Blockchain
1. Web3.js
2. maticJS
3. NodeJS server

## Instructions to run

* Install python dependencies by running ```pip install -r requirements.txt```

* Install all node dependencies in the matic folder using ```npm install``` and Execute ```python3 app.py``` with ```npm start``` to start the app

* Head over to localhost, you will be prompted with a signup page, enter any username and password. You may be required to login using these later on.

* Look into the camera, and register your face with the system.

* Head over to ```localhost/camera-in```, the url for any camera at the check in stage in the public transport system. Once you're recognised, close the tab.

* Open ```localhost/camera-out``` and repeat the process. You will be showed as checked-out in the system and money will be deducted from your wallet.

* Check ```localhost/dashboard``` to see the updated balance.

