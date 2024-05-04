# gorest-test-automation

This repository has the necessary files to test the gorest Api with postman end-to-end tests.

Postman files:   
Users.postman_collection   
Posts.postman_collection   
Comments.postman_collection   
Todos.postman_collection   
Test.postman_environment.json   

Getting started

1. Clone the repository

2. Import the collection and enviroment files to postman:
![Screenshot 2024-05-04 121645](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/c2659349-582b-4a30-8c70-165e711b7a32)

2. Define the gorest api key in environment variables
Environments > Test > token
![Screenshot 2024-05-04 121842](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/e444fad7-8c66-4803-8881-d2cae7547fd4)

3. Make sure you select the Test environment by checking the Test checkmark
![Screenshot 2024-05-04 122126](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/64da52dd-b1c8-4596-9b18-82477515a96f)


How to run a collection
1. Go to collections, select the 3 dots next to the collection you want to run and press run collection
![Screenshot 2024-05-04 122624](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/4f5a997a-902d-4760-99af-683c91c4262b)

2. Configure the run setting and press run
![Screenshot 2024-05-04 123128](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/7dbd2266-67c3-4179-b0ae-bb18bb22cad0)

Note: you can run the collection manually or schedule automatic runs. 


How to execute load tests

1. On collections select the collection you want to test and select the 3 dots next to the collection and press run collection
![Screenshot 2024-05-04 122624](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/4f5a997a-902d-4760-99af-683c91c4262b)

2. Here select the Performance tab, configure the test and press Run
   ![Screenshot 2024-05-04 123546](https://github.com/rubenmpereira/gorest-test-automation/assets/156867735/94896db9-f9f4-4ea0-9fe0-e2dde4328777)
