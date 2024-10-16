## Automation projects

This repository contains some of my automation projects

### 1. [Printer Status Automation](https://github.com/mvarrone/printer-monitoring)
Related repository: [Simulate IP Printer web server](https://github.com/mvarrone/simulate-ip-printer-webserver)

**Description:**  
Developed an automated solution to monitor the status of printers both for business purposes and personal use at home

**Outcome:**  
Created a Dockerized script capable of checking toner levels and drum status metrics. The script also sends email alerts when predefined conditions are met.

**Supported Devices:**  
Applicable to Brother IP printers. Can be extended to other vendors.

### 2. [Hikvision IP Camera Automation](https://github.com/mvarrone/check-rtsp-camera-status)

**Description:**  
Developed a solution to monitor the status (alive) of multiple Hikvision IP cameras

**Outcome:**  
Implemented a script with multithreading to speed up execution. No email alerts are configured.

**Supported Devices:**  
Applicable to monitoring purposed of Hikvision IP cameras

### 3. [Automation for Machine Learning Specialization on Coursera](https://github.com/mvarrone/coursera-scripts)

**Description:**  
Developed a script to automate the creation of a folder and subfolder structure, with a `README.md` file in each folder in the context of a Machine Learning Specialization on Coursera's platform which consists of multiples courses.

**Outcome:**  
Outcome is a structure of folders and subfolders to each lesson in which a `README.md` file is automatically populated with sections in **H2 headers** (e.g., `## Section`) corresponding to the title of each video in the specialization.  

**Supported Courses:**  
- **ML Specialization:**: 3 courses 

**Future plans to apply it** 
- **DL Specialization:** 5 courses

### 4. [Documentation Generation in Postman for Hikvision IP Camera API](https://github.com/mvarrone/hikvision-nvr-postman-collection)

**Description:**  
Created documentation in Postman based on the REST API documentation for Hikvision IP cameras, extracted from three PDF files found online.

**Outcome:**  
Developed an API in Postman consisting of a collection of requests and two environments (one for sending requests in a LAN environment and another for WAN)

**Supported Device:**  
Specific to a particular Hikvision NVR model

> [!NOTE] 
> 
> When testing on other models, some requests may not work due to differences in API implementation. Some NVRs might offer more features and APIs, while others may support fewer. If using a different model, adjustments may be required.

### 5. [Automation for pushing changes using git](https://github.com/mvarrone/git-utils)

**Description:**  
Developed a script able to automate the process of executing commands in order to push changes to a repository

**Outcome:**    
Commit pushed to GitHub in a quick way

**Applicable to:**  
Applicable to each push process you use in a daily basis