## Lab 32: Lambda Warmers and Triggers
Let’s use Lambda to handle database changes in real time!

## Feature Tasks
* Java Insert/Update Functionality
- [x] Create a lambda function, in Java, that can add a record to your Taskmaster table.
- [x] Run this only in “Test” mode
- [x] It should receive the same object that your API was handling earlier.
- [x] Repeat for “PUT” / update functionality
- [x] Do NOT handle images at this point.
- [x] You might want to keep this warm…

* Javascript or Python
- [x] Create a lambda function that will handle a Dynamo Event
- [x] Initial Task: Log out the deltas
- [x] Stretch Goal: Update the history!
- [x] Setup a Dynamo Trigger
- [x] Configure your DynamoDB Table to invoke your lambda function on database change operations.

## Collaborative Acknowledgement 
* Trevor Dobson