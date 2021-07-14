### Collateral loans Risk assessment

### Steps

- Download the zip file of Collateral Loans-risk assessment
-  Extract the zip file.
-  Import the file into spring tool suite.
- Open port localhost:9090/portal/login
-  Login as user  
- Enter the username:user and password:user
-  Create a loan by entering the required details.
-  Check the status in applied loan.
-  Logout from the customer page.
- Now login as Admin with the credentials ( username: admin and password: admin)
- Go to accept/reject application. Accept the required loan.
- Move to activities page and go to customer loan details.
- Enter the loan Id, customer Id in order to fetch the necessary details.
- Go to activities page and open "Save the collateral details"
- Either choose cash/real estate and enter the details and save them.
- Go to activities and click to open risk management.
- Enter the loan id and fetch the risk details.
- Click on "Check collateral details" and enter the loan id to fetch the collateral details.
- Logout from the portal.

### Database ports 

##### Authorization 
- Port : http://localhost:8081/auth/h2-console
- Driver Class : org.h2.Driver
- JDBC url : jdbc:h2:mem:auth

##### Loan 
- Port : http://localhost:8100/loan/db
- Driver Class : org.h2.Driver
- JDBC url : jdbc:h2:mem:loan

##### Collateral 
- Port : http://localhost:8000/collateral/db
- Driver Class : org.h2.Driver
- JDBC url : jdbc:h2:mem:collateral

##### Risk 
- Port : http://localhost:8082/risk/db
- Driver Class : org.h2.Driver
- JDBC url : jdbc:h2:mem:risk

##### Portal 
- Port : http://localhost:9090/portal/login

<h2>Activity Page</h2>
![WhatsApp Image 2021-07-14 at 10 16 45](https://user-images.githubusercontent.com/54927584/125572319-020df935-433a-4af1-9ec8-bdf807bd6fb0.jpeg)
Admin Login Page
![WhatsApp Image 2021-07-14 at 10 16 45 (1)](https://user-images.githubusercontent.com/54927584/125572348-5214b873-ab53-430b-8dcb-14f4d0966baf.jpeg)
List of All Activities
![WhatsApp Image 2021-07-14 at 10 16 45 (2)](https://user-images.githubusercontent.com/54927584/125572356-c5e54324-b9ac-4a6f-97b8-8e11776271b8.jpeg)
Loan Applications
![WhatsApp Image 2021-07-14 at 10 17 19](https://user-images.githubusercontent.com/54927584/125572369-3658f670-5372-4763-9dc8-8c7abe65da77.jpeg)
Loan Application Submission
![WhatsApp Image 2021-07-14 at 10 17 20](https://user-images.githubusercontent.com/54927584/125572376-1394def9-a9fc-431c-bcea-142898e1c60e.jpeg)
Fill Loan Form Details
![WhatsApp Image 2021-07-14 at 10 17 48](https://user-images.githubusercontent.com/54927584/125572385-e08b8578-9c37-4312-93bb-4aa4980f72ae.jpeg)
Main Menu
![WhatsApp Image 2021-07-14 at 10 18 21](https://user-images.githubusercontent.com/54927584/125572391-eed4ef06-8563-48b2-bca4-68c7db8d3396.jpeg)



