# Steps to create django project
1. Create empty folder with name of your project.
2. Open folder with Visual Studio Code
3. Go to __Help__ -> **Show All Commands**
4. Find and select from commands "__Python: Create Environment...__" -> select "**Venv**" -> select any _Global_ python interpretetor
5. Go to **Terminal** -> **New Terminal**. Pay attention when you open new terminal your virtual environment must be activated. On command line you'l see the `(.venv)` prefix.
6. On terminal write command  
$ ```pip install django```
7. Next write command  
$ ```pip freeze > requirements.txt```
8. Next create project  
$ ```django-admin startproject [project_name] .``` 
here pay attention that my command has `.` at the end
9. Next create django application  
$ ```python manage.py startapp [app_name]```
10. Inside of your project(root) folder create file with name `.gitignore`
11. On your browser go to the url [gitignore.io](https://gitignore.io)
12. in the opened page add tags inside search bar, `Django`, `Python`, `venv`, `VisualStudioCode`, `Pycharm+all`. And click **Create** button
13. On the opened page select all (CTRL + A), copy (CTRL + C) and paste (CTRL + V) into your `.gitignore` file.
14. On your vs code account (Left bottom corner) chech that no one logged in to their GitHub page. If logged in log out
15. Now we are going to set up git. On terminal write command to initialize local git repo  
$ ```git init```
16. We have to set up user details, user.name and user.email. Pay attention email you have to set up same with your github primary email.  
$ `git config user.email myemail@gmail.com`
17. And user.name   
$ `git config user.name yourname`
18. Add your changes to git index to commit  
$ ```git add .```
19. Commit your chages  
$ ```git commit -m "Created new django project"```
20. Add remote repository  
$ ```git remote add origin [url-of-your-blank-remote-repo]```
21. Push to your remote  
$ ```git push --set-upstream origin master```