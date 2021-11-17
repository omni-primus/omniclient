# OMNI Client
Webapp to simulate a League of Legends Champion Select 

## Required stuff to contribute

### An IDE. 
Ha who would have guessed. I am using Visual Studio Code, but there are obviously others out there.
(Visual Studio Code things:) For this project it's helpful to install some plugins. Go to `File > Preferences > Extentions` and search for Vue, ESLint and Git History and install them to VSC.

### node.js
I am using npm for compiling and running js. You can download it here: https://nodejs.org/en/


## Initiate the project
- Go to your directory where you want to put the OMNI Client. 
- Open the Command Line and enter following command:
`git clone https://github.com/omni-primus/omniclient.git`
- it might ask you for your Github user credentials.
- now open the new created folder in your IDE
- if you haven't installed Vue yet: In VSC go to `Terminal > New Terminal` and enter `npm install -g @vue/cli`
- after installing Vue you should be able to check the version of Vue by entering: `vue --version` in the terminal

Now the project should be installed on your local maschine. To see the frontend you gotta start a local server. You can do that by entering: `npm run serve` in your IDE command line. You should now see the frontend in your browser if you go to `localhost:8080`

## Git Stuff
Collaborating with git can be very challenging and will only makes sense for you when you start working with it but here are some important things to consider:
>always create a branch before you start working on something
```
git branch branchName
git checkout branchName
```
This is important because if we both work on the same files we do not overwrite our changes and have a better overview overall.

After editing your routin looks like this:
```
git commit -m "commit message"
git pull origin main
git push
```

The commit command collects all changes that were made and puts them on your local history. Pull gets you the latest changes from the main branch (if it says you have to merge something don't do it unless you know what you're doing). Push transports your local changes to the git server (only push if your pull was successfull).



