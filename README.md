# Project--Hadoop-11

<table>
  
  **In this project we will be working on creating the workflow for OOZIE and its gonna be an amazing skills to have in your toolkit.**.<br></br>

Lets learn about **OOZIE** first before diving into its workflow..<br></br>

**What is OOZIE**?<br></br>

Oozie is a workflow scheduler system to manage Apache Hadoop jobs.<br></br>

Oozie Workflow jobs are Directed Acyclical Graphs (DAGs) of actions.<br></br>

Oozie Coordinator jobs are recurrent Oozie Workflow jobs triggered by time (frequency) and data availability.<br></br>

Oozie is integrated with the rest of the Hadoop stack supporting several types of Hadoop jobs out of the box (such as Java map-reduce, Streaming map-reduce, Pig, Hive, Sqoop and Distcp) as well as system specific jobs (such as Java programs and shell scripts).<br></br>

Oozie is a scalable, reliable and extensible system.<br></br>

**Actions in Workflow**

In this workflow we will create perform two main actions.<br></br>

First we will execute scoop to extract the movielens table from the given dataset.<br></br>

Secondly we will insert the Hive Script into insert the table into the extracted data and save it at the output directory where we will run sql queries to extract top 10
movies in our dataset.<br></br>

**What is Scoop?**<br></br>
Sqoop is a command-line interface application for transferring data between relational databases and Hadoop. The Apache Sqoop project was retired in June 2021 and moved to the Apache Attic.<br></br>

**What is Hive?**<br></br>
Apache Hive is a data warehouse software project built on top of Apache Hadoop for providing data query and analysis. Hive gives an SQL-like interface to query data stored in various databases and file systems that integrate with Hadoop.<br></br>


**I have briefly attached the steps to follow in the oozie.txt**.<br></br>

In this project the focus is on creating the workflow for oozie consisting of these two actions and then if reaches end node successfull it gonna come to end state and 
if it fails then it will exit from the current node.<br></br>

**Important Note- Go through the dataset before seeing the workflow.**



</table>

**So what are you waiting for..? Jump to the code to get started. As usual for any doubt or query see you in pull request section 😁😂. Thanks Again!**
