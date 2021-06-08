# Project Title

This project is developed using Tuya SDK, which enables you to quickly develop smart devices, branded APP, cloud development project, etc. For more information, please check Tuya Developer Click and Connect Challenge: https://pages.tuya.com/develop/ClickAndConnect_TuyaDeveloper?_source=e9684c7ca6b31e7221c8420f5af94631

# Objective

To Consume the Open Source API provided by Tuya's IOT Platform

## Getting Started

Navigate to : https://www.tuya.com/
Select the option: Cloud Development

### Prerequisites

Case 1: If you are a first time user:
Click on : Sign Up,
Enter Email address and password of your choice
Navigate to Email inbox and verify your account

Case 2: If you have an existing account:
Click on : Login,
Login with the existing credentials


## Achieving the Objective
## Step 1: Create a project
1. Create a project named: IOT Challenge
2. Choose the development method as : Custom development and choose availability zone as per your interest
## Step 2: Configuration wizard
![image](https://user-images.githubusercontent.com/20831296/120845834-f74d5380-c58e-11eb-9f6c-919c325c7380.png)

3. Select the Country Code and Weather Service (Edition：Trial Version) APIs

 ![image](https://user-images.githubusercontent.com/20831296/120845596-accbd700-c58e-11eb-89df-68bd9157056e.png)
4. Click on Authorize option
5. Verify Configuration wizard is displayed
## Step 3: Link devices
6. Create assets.
   You can manage devices and authorization in a centralized manner by asset ID.
7. Add devices.
   After you create an asset, you can add devices
   
### Steps to extract API credentials:
1. On the Projects page, click the created project to enter the details page. Click the API tab, click Go to    Authorize and click Subscribe beside the unsubscribed API products in the drop-down list.
2. Authorize the subscribed API products to the project.
   On the API page of the project, you can view the subscribed API products for the project. Also, you can click Go to Authorize to add API products.
   
   ![image](https://user-images.githubusercontent.com/20831296/120845700-cb31d280-c58e-11eb-9ec6-73bd1b006173.png)

3. Navigate to Projects
4. Select the created project from dropdown and click on project overview
5. Verify Access ID/Client ID: ctnjqj7wan4f2t50ewie
           Access Secret/Client Secret: ******************************** are displayed.
6. Navigate to tab: API
7. Verify Selected API in (step 5) are listed

### Debug API Explorer:
Log in to the Tuya IoT Platform.
Click Cloud > API Management > API Explorer.
On the API Explorer page, you can make an API call.
Select a project.
Select an API product.
Select an endpoint. For more information, see Endpoints.
Select an API.
#### Note: Click the View Document tab to view the parameter description.
Click the Debugging Results tab to view the request URL and response.
Configure API parameters.
Click Submit Request.

### Security:

1. Incase if IP restriction is needed:
Cloud Application IP Whitelist option can be used
Then only selected IP's will have access to consume the API.

# Import the Postman Collection and refer Video (file name: Usage.webm) for a working demo.

# Resources needed: Postman(latest version), collection can be downloaded from the repo.

# Supporting documents link: https://developer.tuya.com/en/docs/iot/call-api?id=Ka7o7ru1julms


