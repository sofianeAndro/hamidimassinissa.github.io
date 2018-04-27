# Add your project to the website

### TL;DR
The following instructions are illustrated in this [video](https://www.youtube.com/watch?v=RhhsrCXs-eg)

### Create a GitHub account (if this is not yet the case)

### Fork this repository
<p align="center">
    <img src="https://github.com/HamidiMassinissa/hamidimassinissa.github.io/blob/lipn/images/how-to-fork-GitHub.png" height="300"></p> 

### Clone the forked repository to your local machine

    $ git clone https://github.com/your-user-name/hamidimassinissa.github.io.git

### Create a new `.md` file for your project
The filename must follow the format `yyyy-mm-dd-Title-of-your-project.md`

    $ cd hamidimassinissa.github.io.git
    $ cd _iot_projects
    $ touch 2018-04-26-my-awesome-project.md

### Add content to the newly created file
Your file must include the following structure:

    ---
    layout: iot-projects
    authors:
        - author 1
        - author 2
        - author 3
    video-id: id of your YouTube, Vimeo, etc. video
    ---
    
    Add here your awesome description
    
    # Hardware description
    add here hardware parts you used
    
    you can make use of lists like this
    * item 1
    * item 2
    * item 3
    
    # Software description
    same thing here for the software you developed
    
    

### Create a new branch

    $ git checkout -b my-awesome-branch

### Add, commit and push your changes

    $ git add 2018-04-26-my-awesome-project.md
    $ git commit -m "Added my awesome project to website"
    $ git push origin my-awesome-branch

### Make sure that your branch is published on GitHub
Go to your repository on GitHub and check if your file is present in the source tree

### Make a pull request
* Go to your repository on GitHub;
* Click on *"Pull requests"* tab;
* Click on *"New pull request"*;
* Choose branches to compare: in your case, it will be your newly pushed branch `my-awesome-branch` which holds the changes you made, and `lipn` branch which is the branch you want your changes to be applied to;
* Click on *"Create pull request"*;
* Add a comment;

### After a quick check, I will merge your changes
Your project will be available on the website shortly after that. Check if everything is ok [here](https://lipn.univ-paris13.fr/~hamidi/iot_projects/) and leave a comment in your pull request if you want to make a further enhancement.
