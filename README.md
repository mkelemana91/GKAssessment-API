# API testing using Jmeter

The aim of this project is perform basic API testing of REST services and Assertions using Jmeter. Tests will also make use of parameters.

## Getting Started

This project is a Jmeter project. To access this project, import this project download the GK Assessment - API.jmx file into your local machine. Navigate to where your Jmeter folder is located in your machine, copy and paste the jmx file into your Jmeter bin directory. Open Jmeter and open the file in Jmeter by clicking File > Open and locate your jmx file.

## Prerequisites

```bash
Download and install Jmeter - https://www.guru99.com/guide-to-install-jmeter.html
```

## End Points
1. http://www.geonames.org/export/geonames-search.html
2. http://www.geonames.org/export/web-services.html#postalCodeLookupJSON


## Test Plan
Run the Test Plan by clicking the Start button. Test cases and assertions are descriptive and tell what the test needs to achieve.
```bash
Structure 
```
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/1.PNG)
```bash
Global configurations
```
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/2.PNG)
```bash
Negative tests to simulate non successful response codes e.g. 404
```
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/3.PNG)
```bash
Positive tests to simulate successful requests and response codes and messages e.g. 200 
```
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/4.PNG)
```bash
View results here - any errors related to assertions will be displayed here
```
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/5.PNG)

```bash
Expected output
```
From Results Tree - only one test must fail (red)
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/5.PNG)

From Assertions Results - No errors should be displayed
![](https://github.com/mkelemana91/GKAssessment-API/blob/master/Images/5.PNG)

