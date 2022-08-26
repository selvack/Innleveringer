# 1 Development Environment and Cloud Deployment 

This is a readme/markdown for assignment 1 in the subject **DAT250 Advanced Software Technologies. **


# Installation
For the software installation development environment, I chose to use Homebrew to install my software. This is after some research and feedback from developers. I just macOS. 
<br />
#### 1. Homebrew
 Homebrew can be found on brew.sh
Open terminal and write this code:
`` /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" ``


``brew -v``
<br />
#### 2.  Java
Installed java through brew with command
``brew install java``

To validate java installation
```java
java --version
openjdk 18.0.2.1 2022-08-18
OpenJDK Runtime Environment Homebrew (build 18.0.2.1+0)
OpenJDK 64-Bit Server VM Homebrew (build 18.0.2.1+0, mixed mode, sharing)
```
<br />

#### 3. Intellij
Installed Intellij-idea from brew
https://formulae.brew.sh/cask/intellij-idea
``brew install --cask intellij-idea``
<br />

#### 4. Maven
Installed maven from brew
https://formulae.brew.sh/formula/maven
``brew install maven``

<br />

#### 5. Git
Installed Git from brew
https://formulae.brew.sh/formula/git
``brew install git``


# Problems under installation
#### 1. Homebrew
When I tried to install Homebrew on my system i got an warning saying that ``opt/homebrew/bin is not in your PATH``
At the end of the installation log the system responded
```sh
=> Next steps: 
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/selvakumar/.zprofile 
eval "$(/opt/homebrew/bin/brew shellenv)" 
```

then my brew was installed
``brew -v ``
``Homebrew 3.5.10``
``Homebrew/homebrew-core (git revision 26b52fe6a6f; last commit 2022-08-25``


#### 2. Java
When i tried to install java through brew i got the error message
``
The operation couldn’t be completed. Unable to locate a Java Runtime.
Please visit http://www.java.com for information on installing Java.
``
After some googling i found that i had to create a symlink for the system Java wrappers to find this JDK [link to solution page https://stackoverflow.com/questions/65601196/how-to-brew-install-java ]
ran this command

# Setting up Git and Heroku
Signed up for github and Heroku

1. Followed the tutorial for Getting started on Heroku with Java
Had to install Postgres before I was able to get started

I had no problem following the tutorial and everything seemed to work fine. 

# Remaining tasks / unsolved problems
I cant get heroku to push files to my github account.


## Link to heroku app
https://shielded-earth-80955.herokuapp.com/
