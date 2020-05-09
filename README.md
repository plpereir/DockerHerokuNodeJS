# App = NodeJS+Docker+Heroku

Dockerizing (Building Docker Images with heroku.yml) a Node.js web app on Heroku

-> https://polar-everglades-15101.herokuapp.com/ url app
-> https://github.com/plpereir/DockerHerokuNodeJS.git

Getting started:

#1 Create a heroku.yml file in your application’s root directory.

#2 Commit the file to your repo:
git add heroku.yml
git commit -m "Add heroku.yml"

#3 Set the stack of your app to container:
heroku stack:set container

#4 Push your app to Heroku:
git push heroku master

#4 open App
heroku open
