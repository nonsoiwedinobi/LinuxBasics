# Exercises 

1. View all of your environment variables with the more command.

`set | more`

![alt text](image.png)

2. Find a method to change the slash(/) to a backslash (\) in the faux microsoft cmd PS1.

`PS1='${PWD//\//\\} \$ '`

![alt text](image-1.png)

 3. Create a variable named MYNEWVARIABLE and put your name in it.

 `MYNEWVARIABLE="Nonso"`

 ![alt text](image-2.png)

 4. Use echo to view the contents of MYNEWVARIABLE.

 `echo $MYNEWVARIABLE`

 ![alt text](image-3.png)

 5. Export MYNEWVARIABLE so that it's available in all environments.

 `export MYNEWVARIABLE="Nonso"`

 ![alt text](image-4.png)

 6. use the echo command to view the contents of the PATH variable

 `echo $PATH`

 ![alt text](image-5.png)

 7. Change your PS1 variable  to "World's Greatest Hacker".

 `PS1="World's Greatest Hacker"`

 ![alt text](image-6.png)