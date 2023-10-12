# EyeQ-Scan

An app made in flutter which detects the severity of Diabetic Retinopath in diabetic patients on a scale of 1-5 (1 being No-DR and 5 being Severe). The app utilizes a **hybrid model** which contains both classical component (pre-trained ResNet 18) and a quantum circuit. This model is deployed on Azure cloud platform and the client side app gets inferences of the images with the help of a REST api developed using FastAPI framework. 

To use application : 
1. Clone this repo
2. Run the following commands
   ``` flutter pub get
       flutter run ```
3. Open the app on your device
4. Upload the fundus scan (you can obtain one from your doctor) in the app. Enter your name, age and diabetic type.
5. Get results and a medical report.
