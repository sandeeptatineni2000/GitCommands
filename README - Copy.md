# Duplicate Basic Git Commands

### Creating repository online for <b>first time</b>

```sh
$ touch README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/saitatineni2000/GitCommands.git
$ git push -u origin master
## put in username and password
```

### When to add thing to ur repository online to show the changes

```sh
$ git add .(to add all untracked files)
$ git commit -m "changes made to the the README.md file for 2nd time"
$ git push
## put in username and password
```


### No more username and password

```sh
$ git remote set-url origin git@github.com:saitatineni2000/GitCommands.git
```

