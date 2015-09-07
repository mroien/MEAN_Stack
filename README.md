# Mean Stack

A simple tutorial to start using MEAN Stack to create a contact list. You can add, edit and delete contact from the list.

To start **Node server** type node server
* You should see Server running on port 3000
After you refesh browser
* You should see I received a GET request

Install **MongoDB** with homebrew for Macs home directory for project. Or Windows way at [MongoDB Downloads](https://www.mongodb.org/downloads)
[Quick guide for install on Mac](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/)

To run MongoDB open a new tab in terminal and type `mongod` use sudo if you don't have permissions
Then open another tab and type `mongo` that opens the mongo shell

## Mongo Commands
* `show dbs`
* `use nameOfdatabase`
 * this switches you to that database
 * the database we are using is `contactList`
* `db.contactList.insert({name: 'Tom', email: 'tom@testemail.com', number: '(444) 444-4444'})`
 * inserts element into database
 * use `([{name: 'Tracy', email: 'tracy@testemail2.com', number: '(555) 555-5555'}, {name: 'tucker', email: 'tucker@testemail3.com', number: '(777) 777-7777'}])`
 * this makes an array of elements
* use `db.contactList.find().pretty()` to print out in JSON format
