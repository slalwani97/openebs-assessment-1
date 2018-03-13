# OpenEBS-Assessment-1

Assessment -1 OpenEBS Offsite Intern

A Docker Image running simple Hello Python Application.

This image shows the name of the user in the browser.

### Follow the steps to run the app in your machine- 

1. Clone the repository

   `https://github.com/slalwani97/openebs-assessment-1.git`

2. Jump to that folder using cd

   `cd openebs-assessment-1`

3. Apply the .yaml files to run the app.

   `kubectl apply -f pods.yaml`

   `kubectl apply -f deployment.yaml`

   `kubectl apply -f service.yaml`

4. Now run the docker run command to give a manual user input to display on Browser.

   `sudo docker run -d -p 4000:80 -e NAME='your-name' slalwani97/openebs-assessment:1`

5. Hit the link in the browser and you may see similar to, with your-name- 


![application](https://user-images.githubusercontent.com/29499601/37311639-102f8242-266e-11e8-81a7-72c6dce1a41a.png)
