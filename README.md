# A02
# Sanid Dzigal, IS117 - 102
## How to set up GitHub Account
1. Go to the GitHub webpage and click Sign Up
2. Enter your username as it appears in your UCID (or username of your choice)
3. In the email box, type in your njit.edu email (or personal email)
4. Set up your password and go next
5. In another browser tab or on another device, log into your NJIT email (or personal email). There should be a GitHub confirmation code. Copy and paste that code or type it in when prompted. (If it does not arrive after 30 minutes, contact NJIT Nexus for Tech Support)
6. After that, you should see your GitHub profile's main page where you will see your GitHub repositories and activity

### To verify your NJIT student status on Github (Important for WebStorm)
1. On your GitHub main page, scroll down until you see something like Apply for GitHub Education benefits
2. Prepare your physical ID card that has a proper sticker like Spring 2025 (if your ID card is not up-to-date, go to the NJIT Parking and ID office located at 142 Warren St.)
3. Enter your information, and take a picture of your ID (make sure the picture file does not exceed 1 MB)
4. Hit apply and the screen should show a message like "Thank you for applying, expect an email with configuration..."
5. If they deny your request, go to the webpage where you applied and it will show you what went wrong. Carefully follow instructions and reapply.
6. Once you get the approval email, you need to wait a couple of days so that GitHub grants you the Student Developer Pack privileges
7. When another email arrives saying you were granted the Student Developer Pack privileges, you are ready to get WebStorm.

## How to create your first GitHub repository
1. Log into your GitHub account using your username and password from the previous step
2. On the GitHub home page in the upper left corner there is a green button "New"
3. Click on that button
4. Type in the name of your new repository
5. (optional) Type in the description for your repository
6. Select the visibility for your repository - public by default, meaning anyone can see it
7. (optional) Check the box to add a README.MD file if you want your repository to have a premade README file
8. Click the Create repository button

## How to set up Git on your PC
1. Go to https://git-scm.com/downloads
2. Select Windows if your PC is running on Windows OS
3. Click 64-bit version (most devices run on 64-bit systems nowadays, if you know your device is 32-bit then click 32-bit version)
4. Download Standalone installer
5. Run the installer
6. Follow the steps through the installation (IMPORTANT! To make your life much easier, make sure to check the box with "desktop shortcut" next to it. Important for the next step)
7. Link your GitHub account with your Git via email or SSH key.

### To permanently link Git and GitHub via the Git Bash terminal
1. Locate your Git Bash app (if you didn't make a shortcut, browse for "Git Bash" app in the start menu)
2. Run the terminal
3. Type in the following command: git config --global user.email "YOUR_EMAIL"
4. (where it says YOUR_EMAIL, change it with the email associated with the GitHub account you created)
5. Hit Enter
6. To check if you did it correctly, type in the following command and your email should pop up on the screen: git config --global user.email

## How to get WebStorm editor (as an NJIT student)
1. Go to https://www.jetbrains.com/shop/eform/students
2. Do the Captcha
3. In the Apply With section click on GitHub
4. Click on the Authorize with Github button
5. It will redirect you to your GitHub account
6. Follow the steps
7. After that is complete, you will be redirected back to the JetBrains site where you need to put a few pieces of information like your current educational status, etc. (IMPORTANT! Do NOT forget to use your ucid email, otherwise they will not grant you access to anything and you have to start the process again)
8. You will then end up on the licenses page, where you will likely see WebStorm on the top of the screen. Click download.
9. Once downloaded, launch the installer and follow the instructions. They might ask you again to verify your status with GitHub, but it should be at most a couple of clicks. Make sure to create a desktop shortcut again.
### Bonus: How to clone the GitHub repository onto your device using WebStorm
10. After installation, launch WebStorm from your desktop
11. If you already created a repository on GitHub, click "Clone repository"
12. Go to your GitHub and open the repository there
13. Click the green "<>Code" button
14. Click copy URL to the clipboard
15. Go to the WebStorm App and paste the URL
16. Choose the directory where you want your repository to reside on your machine
17. Click clone, and you will see your GitHub repository open as a project in WebStorm

# Part 2- Glossary of terms
* **Branch** - In Git, a branch is a new/separate version of the main repository. Git branches are effectively a pointer to a snapshot of your changes. When you want to add a new feature or fix a bug no matter how big or how small, you spawn a new branch to encapsulate your changes.
* **Clone** - Cloning a repository on GitHub is the process of copying a repository's data to your local computer. This includes all versions of files and folders, as well as the repository's history and branches. 
* **Commit** - Similar to saving a file that's been edited, a "commit" records changes to one or more files in your branch.
* **Fetch** - Fetch is a primary command used to download contents from a remote repository to a local machine.
* **GIT** - Git is a free, open-source version control system that helps developers track changes to their code. It's the most widely used version control system in the world. 
* **Github** - GitHub is a website that helps developers store, track, and collaborate on software projects. It's a social network for programmers that encourages collaboration and sharing. 
* **Merge** - Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by Git branch and integrate them into a single branch.
* **Merge Conflict** - A "merge conflict" on GitHub occurs when two different branches of code have made changes to the same part of a file, causing Git to be unable to automatically combine those changes during a merge, requiring manual intervention to decide which version of the code to keep; essentially, it happens when multiple developers modify the same section of code simultaneously, leading to conflicting versions that need to be resolved manually.
* **Push** - The git push command is used to transfer or push the commit, which is made on a local branch in your computer to a remote repository like GitHub.
* **Pull** - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
* **Remote** - A remote repository in Git, also called a remote, is a Git repository that's hosted on the Internet or another network.
* **Repository** - A Git repository is a virtual storage space for a project's code, files, and their revision history. It's a key part of Git's version control system, which helps multiple developers work on a project simultaneously. 
