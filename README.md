# Tip_calculator

How to run on your pc
Follow the steps:
(It works for me)

Step 1 : Download the zip file and extract it in a folder. <br>
Step 2 : Click on New < Import Project in Android Studio and then select the app folder in the extracted folder. <br>
Step 3 : Open build.gradle file and paste the following code in android <br>
          task wrapper(type: Wrapper){
             gradleVersion = '7.2'
           }
           
Step 4 : Build the project and run it 
