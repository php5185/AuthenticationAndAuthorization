# Assignment #3

## Description

For this assignment, we implemented a web application with authorization and authentication security tactics.

## Frameworks

We use Java Spring to create the server and to include the Security Tactics.

## Steps to run
In order to run this project you must:
- Open this project with your preferred JAVA IDE
- Install the project's dependencies.
- Run the code.

The application should be available at `localhost:8080`.

Right now we have two users created: user (password: `password`) and admin (password: `password`)

Both users are able to log into the system but just `admin` has the proper role to access the `localhost:8080/admin_page`.
If you try to access it as `user`, you should see a forbidden error message because `user` it's not allowed to use that resource.
