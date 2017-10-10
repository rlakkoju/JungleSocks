# JungleSocks
AcceptanceTestScript
Created a test data in a Json file for name of the products and the taxes applied for the states
For Automation Scripts, I have used Java with Selenium WebDriver and TestNG
I have used Page Object Model, where the page objects and the reusable code is written in the separate package as 'Page Objects' and the test scripts are written in another package.
Test run Method:  
Read the json file into string from the file and convert the string into Json objects
For each state in Json file repeat the checkout with quantities populated by each product
Calculate the tax and the total in the test itself and do assertion to assert the values displayed in the second page
