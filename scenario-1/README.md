# scenario

This hypothetical scenario will attempt the following: 

- A new application will be deployed. It needs:

* A new pdb
* A separate diskgroup to house the pdb
* Set init parameters to make sure that files end up in the new diskgroup
* A new app-user, which should get its permissions from a role
* A separate tablespace for the app-user
* A service which the application can use
