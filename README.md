[Live demo](http://damp-cliffs-9394.herokuapp.com/)

[Live demo](http://stark-woodland-6396.herokuapp.com/)

Just a little example chat app using Rails 4, Ruby 2, and WebSockets.

Lots of code stolen from [websocket-rails-example-project](https://github.com/DanKnox/websocket-rails-Example-Project)

Heroku Setup Instruction

Install heroku toolbelt

1. Git Clone
2. Cd to project folder
3. git init
4. git add .
5. heroku login
6. heroku create
7. git push heroku master
8. heroku labs:enable websockets
9. heroku run rake
10. changing the time zone to new york 

    heroku config:add TZ="America/New_York"


MIT License
