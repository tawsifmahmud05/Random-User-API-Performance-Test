# Random-User-API-Performance-Test
## Prerequisite
  - Java jdk8 must be installed and set with environment
## Technology and tool used
  - Jmeter
  - Excel
## Testing Link
  - https://random-data-api.com/api/v2/users
## How to run this project
  - Clone this repsitory
  - Open jmx file using Jmeter
  - Configure as you want to test
  - Then start load/stress testing as required
## Load Test Scenario
Here Load testing  is performed using [RandomUser API](https://demoqa.com/BookStore/v1/Books) where the expected load is 10000 per hour. Severall tests has been performed for 60s,300s,600s and 900s load using Jmeter. The tests having TPS breakdown are summarized in excel spreadsheet and HTML report for the last test of 900s having 2500 users.
### Load Testing TPS and Test Breakdown
  ![Load Test](https://user-images.githubusercontent.com/85132422/193652169-4d383b40-77f6-4d7e-b0fa-befbca9cfa35.PNG)
### Load Testing HTML Summary Report
  ![Load testing Report](https://user-images.githubusercontent.com/85132422/193652367-31839eb7-bf98-4443-8713-f2444278ce2f.PNG)
## Stress Test Scenario
Here Load testing  is performed using [RandomUser API](https://demoqa.com/BookStore/v1/Books) where the starting load is 10000 per hour. Severall tests has been performed for 60s,300s,600s and 900s load using Jmeter. The tests having TPS breakdown are summarized in excel spreadsheet and HTML report for the last test of 900s having 66000 users where 1% error is found.which is the bottleneck TPS/Stress test point.
### Stress Testing TPS and Test Breakdown
  ![Stress test](https://user-images.githubusercontent.com/85132422/193652471-4b141cef-56e2-43b9-a893-26e703609dc5.PNG)

