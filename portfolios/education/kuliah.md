# Summary

## Skills and Tools

- **Programming Languages:** Dart (Flutter), Golang, Python
- **Tools & Technologies:** Firebase, Docker, AWS EC2, Linux, LetsEncrypt
- **Machine Learning:** PyTorch, YOLOv5, TFLite
- **Others:** Android Development, iOS Development, REST APIs, Microservices Architecture

<br>

## Summary of Projects

- **Parking Slot Monitoring System (Final Project):** Machine learning-based system to monitor and display parking slot occupancy status in real-time.
- **Pneumonia Detection App:** Mobile app developed in Flutter to fetch TFLite model from an API, perform inference inside the app, and display results to the user.
- **Loan Management App:** A simple app developed to facilitate the loaning of machinery items.
- **Cleaning and Disinfection Robot:** A robot equipped with sensors to measure room humidity and particle count, also capable of dispensing disinfectant.
- **IOT:** IOT Course Project using html, css, and mostly javascript

<br>

## Links

- [Playstore App: Parking Slot Monitoring System (Final Project)](https://play.google.com/store/apps/details?id=com.nss_productions.parkyr)
- TODO: Final Project Links

<br>


# University Experience at Universitas Prasetiya Mulya (2019 - 2023)

_Universitas Prasetiya Mulya - BSD Campus_  
Address: Jl. Edutown No.1, BSD City, Kec. Pagedangan, Kabupaten Tangerang, Banten 15339  
Website: [prasetiyamulya.ac.id](https://www.prasetiyamulya.ac.id/)  

<br>

## Major: Computer Systems Engineering
Program Info: [S1 Computer Systems Engineering](https://www.prasetiyamulya.ac.id/en/undergraduate-programs/s1-computer-systems-engineering/)

During my time at Universitas Prasetiya Mulya, I delved into a comprehensive Computer Systems Engineering curriculum, studying everything from basic physics, calculus, and discrete mathematics to advanced topics such as IoT system development, machine learning, artificial intelligence, and data science. This broad knowledge base allowed me to be adaptable and innovative in my projects and collaborations.

<br>

---

<br>

## Final Project: Parking Slot Monitoring System

For my final project, I developed a parking slot monitoring system using machine learning. The system can predict from an image which parking slots are occupied and which are not, then present this information in an easily readable format for users. This project consisted of several parts:

<br>

### Backend System
**Skills and tools: Docker, Flask, Golang, Firebase, PyTorch, AWS EC2, Linux**

The backend system, consisting of two dockers, handles API calls and inferences. This system was released on AWS EC2, running in a Linux environment, and is HTTPS-enabled with its own domain name using Let's Encrypt. One docker is dedicated to inferences and runs on Flask, while the other is responsible for the API and is implemented in Golang. The Golang docker is connected to Firebase and stores data there. Flask, with its Python environment, can run PyTorch inferences using its library. The system works as follows: the API receives an image, sends the image to the inference docker, receives a prediction, transforms the prediction into a format readable by the frontend, and finally saves it to Firebase Firestore.

<br>

### Camera Server
**Skills and tools: Golang, Imou Camera API**

The camera server periodically sends photos (every minute) to the backend system. This server also runs on Golang and utilizes the Imou camera API. While multiple servers are intended for future scalability, currently there is only one for demonstration purposes.

<br>

### Frontend
**Skills and tools: Flutter, iOS, Android, Firebase**

The frontend was built with Flutter for both iOS and Android applications. The app displays the parking slots using Flutter's Canvas. The UI resembles a map with parking slots represented in four colors: green (empty), red (occupied), orange (invalid or error), and grey (not predicted, meaning the slot cannot be covered by the camera for prediction).

The app can be downloaded from the [Google Play Store](https://play.google.com/store/apps/details?id=com.nss_productions.parkyr).

<br>

---

<br>

## Notable Projects

<br>

### Research Assistant: Pneumonia Detection App

**Skills and tools: Flutter, TFLite**

As a research assistant, I created an app using Flutter for pneumonia detection. The app fetches a TFLite model from an API, conducts an inference within the app itself, and displays the result to the user. This project aimed to streamline and digitize the process of preliminary pneumonia detection for quick reference and ease of access.

> **Note:** Detailed project information is private/disclosed.

<br>

### Machinery Loaning App

**Skills and tools: Flutter**

I developed a simple Flutter app for loaning machinery items. The purpose of this project was to streamline the process of borrowing and lending machinery, by providing a digital platform where users could easily manage their transactions.

<br>

### Cleaning and Disinfecting Robot for COVID-19 Prevention

**Skills and tools: Robotics, Sensors, Embedded Systems**

I contributed to the creation of a cleaning robot, designed as a preventive measure against COVID-19. The robot is equipped with several sensors to monitor room humidity and check for an excess of unwanted particles. Additionally, it features a disinfectant spray for active disinfection, not just cleaning. This project aimed to leverage technology for health and safety purposes in the context of the COVID-19 pandemic.

<br>

### IOT

**Skills and tools: IOT, Sensors, Website**

[IOT Course Project using html, css, and mostly javascript](https://github.com/nicholas-stancio/IOT/tree/main)