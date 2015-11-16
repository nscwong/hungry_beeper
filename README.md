###Hungry_beeper
CS M117 Project


#Web Interface of Hungry Beeper

##Introduction
The web interface of Hungry Beeper is meant to be accessed by individual restaurant to manager the current queue for the restaurant. They may choose to inform a customer that their table is ready, update the wait time, and approve new customers requesting to join the queue. 


### Usage
1. Add a customer to request queue. Request Queue will display new request. 
2. Modify the wait time and click approve. Queue will show the new customer in line. 
3. Click Table Ready when table is ready.
4. Click X to delete customer from queue when done. 

+ You can also delete the request if you don't approve. 

### Current functions
--
+ Display restaurant info 

--
+ Display Queue - with table ready button
+ Need to add modification to wait time. Maybe Update from/to parse every 5 minutes or so.
+ decide whether to use web to update parse, or have another system to update. 

--
+ Add customer to request queue. 
+ Allows owner to approve with a wait time or delete. 

--
+ Restaurant lookup to change restaurant
+ We may need to add password protection for each restaurant



### Back Log
+ (removed) Add Customer to wait Queue via customer ID. 
+ (completed as request queue) Need to improve this so that it is a temporary queue and web just needs to approve. 
+ (removed) Currently is just a proof of concept that adding works. No restaurant is actually going to remember CustomerId...