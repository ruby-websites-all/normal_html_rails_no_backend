## fut here will be baselines...
1) put a route into the rails application.... 
```  has sub list```

2) put something a little more involved into the view.
```  has sub list```

1) folder structure:
```  list will show here```
```    sub files here```
## There is nothing here yet. <br>Each one of these projects is currently on step 0.

![screen shot 2017-05-22 at 12 30 35 pm](https://cloud.githubusercontent.com/assets/11463275/26319260/539a6d18-3eec-11e7-9c85-f9785f130ea0.png)






Learned so far: 
<br>(1) <b>config/local/</b>, allowing a website to be written into different languages.
<br>(2) Heroku addons. <b>Redis to Go</b> must be added via the resources tab due to Project dependency.

## Installation

1) brew install postgresql
2) brew install redis
3) brew install mysql
4) brew services start postgresql
5) brew services start redis
6) brew services start mysql
7) install rvm and rails through ... rvm website.
8) ```rvm install 2.3.3```
9) git clone *thisreponame*
10) ```cd *thisreponame*```
11) ```bundle install```
12) rails s

## deploying to heroku(Rvm must be 2.3.3 or greater)
1) brew install heroku
2) heroku login 
3) heroku create
4) git push heroku master
5) heroku rake db:migrate
6) need to add Redis To Go add on via heroku dashboard.
7) <br><pre>https://dashboard.heroku.com/apps -> yourappname -> ResourcesTab -> find_more_addons -> install Redis To Go</pre>
8) git commit --amend
9) git push heroku master --force-with-lease


http://stackoverflow.com/questions/10661026/deploying-redis-to-heroku-unable-to-connect

# Overview: A web app for: 
1) Group Interaction 2) Group Knowledge 3) Onboarding, getting users: the right direction
