# Jenkins
## Jenkins - Overview
## Jenkins - Installation
#### Download Jenkins
You can download Jenkins following link [Jenkins](https://jenkins.io)
#### Starting Jenkins
Open the command prompt. Browse to the directory where the jenkins.war file is present.
``` cpp
D:/> java -jar Jenkins.war
```

#### Accessing jenkins
Once jenkins is up and running, one can access jenkins from the link - **http://localhost:8080**


## Creating your first Pepeline
#### What is a jenkins pipeline?
**Jenkins Pipeline** is a suite of plugin which support implementing and integrating continuous delivery pipeline into jenkins.</br>
To get started quickly with Pipeline:</br>
![](Image/firstpipeline.PNG)
1. Copy one of the example below into your repository and name it **Jenkinsfile**.
2. Click the New item menu within Jenkins.
3. Provide a name for your new item(e.g **My Pipeline**) and select **Multibranch Pipeline**
4. Click the **Add Source** butto, choose the type of repository you want to use and fill in the details.
5. Click the Save button and watch your first Pipeline run!
## Running multiple steps

