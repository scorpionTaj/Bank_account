# Bank_account
This article focuses on how to create a bank account system using C language and File handling in C.
Approach:
Let’s discuss the approach in detail, covering all the functions and their explanation in detail: 

1 - Create a Menu in the main function and create different functions for the Menu, which will be called using switch case statements. There are four different functions-
  account()- This function is used to create a new account.
  transfermoney()- This function is used to transfer money to the account
  checkbalance()- This function is used to check the balance in the account.
  login()- This function is used to login into the account.
2 - First, create an account of our user by calling the account() function after the creation of an account, store all the data into a file using file handling functions.
3 - Then the user is able to transfer the amount to other users, for that transfermoney() function is called, and for checking the current balance in the account call checkbalance() function.
Concepts of file handling will be used to store the data of the users, and then read all data from that particular file, store structures in a file because they are easy to write and read.
![Screenshot 2022-06-05 011927](https://user-images.githubusercontent.com/96800858/172029791-eaa8677f-83d9-41a7-81a4-d1de409220fd.png)
