# Social Nest App
 
![Design preview for the Social Nest coding challenge](./images/icons-png/user-white.png)

## Designing a Social Networking App

* A signup process
* A login form
* A logout facillity 
* Session control
* User profiles with uploaded thumbnails
* A member directory
* Adding members as friends
* Public and private messaging between members
* Styling the project

## The Functions

* createTable
 * Checks whether a table already exists and, if not, creates it
* queryMysql
 * Issues a query to MySQL, outputting an error message if it fails
* destroySession
 * Destroys a PHP session and clears its data to log users out
* sanitizeString
 * Removes potentially malicious code or tags from user input
* showProfile
 * Displays the user’s image and “about me” message if they have one
