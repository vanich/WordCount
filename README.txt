To execute the Program please follow the following steps.

1) unzip the file wordcount.rar from github
2) I have created the mongodb in our local machine so please use localhost as server name and portnumber 27017.
    Also I have downloaded the mongo db java drivers and are present in lib folder .
3) use the following commands to create a class file 
   javac -cp ".;lib\*;" WordCount.java
4) use the following commands to create jar file  
   jar -cvf WordCount.jar WordCount.class lib\*
5) To execute 
   java -cp WordCount.jar;lib/*;. WordCount sample3.txt