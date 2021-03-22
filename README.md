# SienaARPrimaryApp
An educational mixed reality application for teaching students complex topics in fields of science.


# What is Git and Github?

  Git is a version control system for computer terminals. Git tracks a directory called a
  repository and the user can specify what files in that directory can be saved in the cloud.
  When a user "clones" a git repository they can start running commands to make changes to the
  files in the cloud so that other team members can "pull" the changes on their local devices.
  
  Github is simply a website to view and manage your Git profile and repositories.
  

# Setup Instructions:

Make an account at https://github.com

Here is a video tutorial to install git, along with cloning repos, and making changes. https://www.youtube.com/watch?v=HVsySz-h9r4

Windows:
  Open Git Bash or prefered terminal.
    
MacOS:
  Open Terminal (You can spolight search or find in launchpad).
  
* At 4:13 in the video, you learn how to configure your github profile with git.

** At 15:10 in the video, you learn how to clone a repo. Watch before doing the next steps so that it is clear.

'cd' into a directory of your choice, (I use Documents) then run the following commands:
- mkdir /UnityProjects       
- cd /UnityProjects
- git clone https://github.com/SienaUnityXRApps/SienaARPrimaryApp
- cd SienaARPrimaryApp
- git status            (this will give the status of the repository and may give you further instruction.)

Close the terminal.

Open Unity Hub.
Click Add in the Projects screen.
Locate our ~/UnityProjects/SienaARPrimaryApp repo directory. ('~' is the location of your user or home folder.)
Open the project with Unity version 2019.4.21f1.  (Install it if you do not have it already.)
Do not update Vuforia if it prompts you to do so. (It probably will... all the time.)
  
Congrats, you've cloned the Siena Primary App for Physcis simulations!

More Git Commands:
https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html
