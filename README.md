# SangBookStore
This is the repository for the website selling bookstore

This is just a testing website using Spring Framework. To run the website on the local machine, you should have Tomcat server installed and running. Additionally, you should have MySQL installed and running at the same time.

To make edit to the site's backend and code, it's recommended that you use IDE tools such as Eclipse.

There is one important note when attempting to run the site on the local machine. DO NOT COPY AND PASTE the entire folder in the working folder created in Eclipse. Instead, you should start a new project and then convert that project into Maven project, then start copying the files in the following order:

1) Create a new package named whatever you want but it's recommended to name it like this sample: com.hccs.edu. After package created, copying all the Java files into the package
2) In the folder that stores all the contents of the website, create the folders that named exactly like the ones found in the source. Then start copying and pasting all files from the source into their respective folders.
3) Copy and paste the servelet file into the folder containing files of the site. The servlet should be place in the same level as the other folders you created in the previous step.
4) Copy and replace web.xml file
5) Copy and replace pom.xml file
6) Save the project.
7) Upload the sample database included in the source to MySQL database.
8) When finished, refresh the database. And then test the project by right-click on the the project and then choose Run As > Run on Server

After the last step, see if you can bring the project up and running on the browser. If not, check connection between the server and the database. Or, check the log shown on the Console tab on Eclipse or on the browser to find and fix the errors.
