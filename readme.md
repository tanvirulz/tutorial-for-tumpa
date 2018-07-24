# Creat new git repo with existing code

1. Create afolder for your project. 
1. Copy all your existing files into that project folder. 
1. Nevigate inside that folder using terminal.
1. Initialize local git repozitory for theproject by executing 

    ````
    git init
    ````

1. Add all the files to git commitmet stage by

    ```
    git add .
    ```
    
1. Now commit the files by 

    ```
    git commit -m "Initial commit"
    ```
    
1. Now log in to github and crate new repository with the same name as your project folder name

1. After creating the folder there will be a section called "…or push an existing repository from the command line"

1. You have to run 2  commands that was specified in this page. For this particular example the commands are:

    ```
    git remote add origin https://github.com/tanvirulz/tutorial-for-tumpa.git
    git push -u origin master
    ```
1. You have to provide user name and password as was prompted by the git terminal

