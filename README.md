# PerformanceCourse

In this project I have created 2 test plans for https://www.demoblaze.com/.

# Technologies

I have used following technologies in this project:
- Java 1.8
- Apache Jmeter 5.5

# Run the Test

- Install Java 1.8
- Install Apache Jmeter 5.5
- Download files from repository
- Open Jmeter
- Open downloaded file in Jmeter
- In CSV Data Set Config change the Filename path to match "users.csv" location on your machine
- Run RampUp or Benchmarh test plan

## Run the Test

1. **Navigate to the project path in the terminal.**
2. **If you want to view the code, enter the command:**
   ```bash
   code .
3. **Open the webTest.csproj file and ensure that all dependencies are up-to-date
4. **In order to build a project, enter the command:**
   ```bash
   dotnet build
5. **Running the test cases can be done by executing the following command:**
   ```bash
   dotnet test --logger "html;LogFileName=test-report.html

## See the List of Open Jobs
1. **Navigate to _location_of_the_project/bin/Debug/net7.0**
2. **Open openJobs.txt file**

## See the Results
1. **Navigate to _location_of_the_project/TestResults**
2. **Open test-report.html file**
