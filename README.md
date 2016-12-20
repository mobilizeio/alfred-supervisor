#Alfred Integration

alfred can help you manage your process

![](http://i.imgur.com/QpJYoQ3.png)


you can manage the entire work flow using `alfred`

after adding the alfred workflow (workflow will be given via slack), you're going to have to define the repository directory
to do so, open alfred box and type `alfred`, then select `show alfred preferences`
now select the `Supervisor` workflow click at the X icon in the top right of alfred:

![X icon here](http://i.imgur.com/yNDwrm7.png)

setup your REPOSITORY_PATH to the absolute path of your repository
![REPOSITORY_PATH](http://i.imgur.com/3wbmYhW.png)

###Now we are all set!

##Alfred workflow Usage
type `env` into the alfred box
the first time you will enter this, you will get this results - which means that the superv is not started.
![](http://i.imgur.com/lJxJIQA.png)

you can hit enter to start the supervisord
after the daemon is started, you can see the list of the processes and the statuses of them

![](http://i.imgur.com/QpJYoQ3.png)

###Now everything is really up and running!

