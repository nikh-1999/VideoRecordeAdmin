# VideoRecordeAdmin

### Technology used : 1. Android Studio 2. Firebase Database 3. Java

In this admin side app our main would be to provide the admin with the list of user and impliment a chat feature so admin can send message to any user.
Approach :- We will use FireBase Realtime database which is NoSQL database and uses JSON. This sync in realtime.

1.Main Activity : - Used for signIn and LogIn purpose. We have used FirebaseUI which provide us a great Signin options with different checks for password invalid email etc

2. UsersList Activity :- This Activity list the users. We use DatabaseRefrence to point to the "Users" node in the JSON tree and take a snapshot. Now we will just loop through
this. and with the help of simple arrayAdapter we will populate the listView.

3. Chat Activity : - This activity impliments the chat feature and we do this with the help of "transactions" which is if there is any new addition in our JSON then it will be
litening for it.
