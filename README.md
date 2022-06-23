# Lab-4.04

### Did you use the same type of route to update patient information and to update an employee department?
No
### Why did you choose the strategy that you chose?
I have used different routes so that the same one is not overwritten, and be able to access the queries from POSTMAN
### What are the pros and cons of the strategies you chose for creating these routes?
Pros: Routes are not overwritten
Cons: There is more code which takes more time to work on and is perhaps less efficient.

### What are the tradeoffs between PUT and PATCH?
The difference between the PUT and PATCH requests is reflected in the way the server processes the enclosed entity to modify the resource identified by the Request-URI. 
In a PUT request, the enclosed entity is considered to be a modified version of the resource stored on the origin server, and the client is requesting that the stored version be replaced.
With PATCH, however, the enclosed entity contains a set of instructions describing how a resource currently residing on the origin server should be modified to produce a new version
