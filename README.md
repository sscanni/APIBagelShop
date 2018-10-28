# Mom and Pop's Bagel Shop API

## Project Overview 

This is the quiz assignment in Lesson 4 under Lesson 14: securing your API

Mom and Pop's Bagel shop has a backend web Flask API.

The program contains a /bagels route that exposes all of the bagels in their inventory, a feature
that only users that are M & P Bagel Shop members can view.

Make the following changes:

1. Add a user class in models.py file to securely store usernames and hashed passwords
2. Add a route for users to register their account by sending a POST request to /users
3. Protect the /bagels endpoint so that only members can view the bagel directory
4. Use the bagel-tester.py file to test the changes
