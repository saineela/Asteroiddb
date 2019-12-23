# AsteroidDB

**Simple, customizable database.**

Why people just can't set up a simple and free database for apps/softwares? They are actually just saving values and getting the values by using the tags. So there is no reason to providing an almost impossible solution for creating online database. We are in 2019. 

So welcome to a new generation in database service. If you want a too simple database which only holds string values, then AsteroidDB is for you. It is based on TinyWebDB (Python version) which is an MIT App Inventor component, and **can be accessed with HTTP requests, this makes AsteroidDB can work in almost every programming language!**

It can be installed on [Heroku](https://www.heroku.com/) with one click, if you don't want to deal with setting up thing (as I did). AsteroidDB is using [Flask](http://flask.pocoo.org/) micro-framework and written in Python, so you can understand that how it is easy to improve the code.

[<img src="asteroiddb-badge.png" width="350" height="100">](https://ysfchn.gitbook.io/asteroiddb/setup-asteroiddb/host)

..or use Heroku one-click deploy button if you know how to use it.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/ysfchn/AsteroidDB)

[Current available methods](https://ysfchn.gitbook.io/asteroiddb/)

***

#### Who is AsteroidDB for?

- For people who wants to create cross-platform apps with using same database service which doesn't require any 3rd party libraries. 
 > For example; Google's Firebase is working very well, however, some programming languages still don't support Firebase officially because of libraries. *(such as C#)* But if your app is supporting Web requests like POST, GET etc. Then AsteroidDB will work for you.
 
- For people who don't wants to deal with setting up database thing. 
 > AsteroidDB supports Heroku's one-click Deploy function, so if you click on the button, a new app will be created from this repo. This means you can just access your web database easily in seconds. 
 
- For people who wants to build own database with own functions.
> If you open the `app.py` file you can see there how data is saving to table. Additionally, you can add more functions if you know Python.

### Thanks

This is a cloned and improved project from [pavi2410/TinyWebDB](https://github.com/pavi2410/TinyWebDB). 
