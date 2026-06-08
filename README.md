# MEG
Minima Enterprise Gateway

This is a Maven project

Gives an http interface to Minima with full user management, admin site and logs

Use if you are an Enterprise wishing to easily integrate Minima into your current teck stack

You need to run a Minima node, enable RPC and connect MEG to it.

To run :

```
java -jar minima-meg-4.0.jar
```

To get a list of options for the cli - simply run :

```
java -jar minima-meg-4.0.jar -help
```

You can set the port, data folder, default login for Minima RPC node etc

You can browse the main admin site at http://127.0.0.1:8080 (or whatever port you have chosen)

You will need to specify a starter -adminpassword on the cli for your initial login and then to add more users 


