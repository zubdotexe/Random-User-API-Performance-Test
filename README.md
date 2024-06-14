# Project Title: Automation of Performance Testing on Random User API using JMeter  
### Project Summary: In this project, the performance testing has been conducted on a random API through Load Testing and Stress Testing. In addition, the capacity value of the API has been measured through Stress Testing. 

## Prerequisites:  
- jdk(LTS version)
- JMeter

## How to run?
### Execute following commands to generate the HTML report:
- jmeter -n -t <filename.jmx> -l <filename.jtl> -e -o Reports
#### Alternative command: 
- jmeter -n -t <filename.jmx> -l <filename.csv> -e -o Reports

## Documentation:
- API endpoint:  
 https://randomuser.me/api

## Links:
- Load Test:  
  https://docs.google.com/spreadsheets/d/1Y3-opYiKyNwfY9HX1DMbIh5ZIgWsIocc6LHCu0eUzpA/edit?gid=0#gid=0
- Stress Test:  
  https://docs.google.com/spreadsheets/d/1Y3-opYiKyNwfY9HX1DMbIh5ZIgWsIocc6LHCu0eUzpA/edit?gid=593434018#gid=593434018
  

## Output:
### Report:
![image](https://github.com/zubdotexe/Random-User-API-Performance-Test/assets/64923600/49823723-dc6f-4961-87ee-dac9f015093d)

### Load Test:
![jmeter-1_load](https://github.com/zubdotexe/Random-User-API-Performance-Test/assets/64923600/4de0234a-2af7-4e1c-bfee-91f82a3069d2)

### Stress Test:
![jmeter-1_stress](https://github.com/zubdotexe/Random-User-API-Performance-Test/assets/64923600/bc0f2ab5-c2df-416f-8039-8c257ef6f340)




