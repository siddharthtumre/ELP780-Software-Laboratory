# How I created my git account today.
Siddharth Tumre - 2021EET2380

Git is a free and open source distributed version control software design to handle how project developments. Git was initially developed to manage the linux kernel development by Linus Torvalds. Every person working on the project will have the same updated code and one can develop individually on different features using branching techniques.

## 1.1 How I Learnt about GIT today.

### **Installing GIT on Ubuntu**
Open a Terminal and run the below commands to install git.

    sudo add-apt-repository ppa:git-core/ppa
    sudo apt update
    sudo apt install git

Then configure the global user name and user email on the system by entering the commands below:

    git config --global user.name "Siddharth Tumre"
    git config --global user.email "siddharthtumre2@gmail.com"

### Once after we successfully install git we can intialize an empty git repository using the below command.

    git init

And then work on some files, save them and and track them using the command given below.

To track all the files:

    git add .

To track a specific file:

    git add <filename>

### Other way of creating a git repository

One can create an empty git repository on websites like _github.com_, _gitlab.com_ or _bitbucket.org_ etc.

Then simply clone the repository using the below command.

    git clone <url>

Then we need to add and commit the changes we made to files nad push it to the repo to make it accessible for everyone.

To commit:

    git commit -m "<commit message>"

To push it to repo:

    git push -u <local branch name> <remote branch name>

## 1.2 The two course mates I shared the document with today
1. Arathi Nair M
2. Ravali Kuchibhotla