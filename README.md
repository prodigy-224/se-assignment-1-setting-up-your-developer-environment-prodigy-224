[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15259671&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1 Select Your Operating System (OS):
Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
How to clean install with Windows 11 Installation Media
This is a way to create a bootable USB drive that you can use to clean install on your current Windows 10 PC .Visit https://www.microsoft.com/en-us/software-download/windows11  and from there, choose the Create Installation Media option then follow the steps below:

Step 1:
Agree to the terms and choose Accept. Let the Setup tool run, and choose Use the recommended options for this PC. Click Next, and   choose USB    flash drive.

Step 2: 
Choose your USB flash drive from the list and then click Next. You'll be prompted and Windows 11 will download to it. Once finished, the installer will switch to Creating  Installation media. You'll know when it's finished, as you'll get a prompt that the drive is ready.
![alt text](1.png)

Step 3:
Once your USB drive is ready, close the installer with the Finish button .Keep the USB drive plugged into your PC.

Step 4: 
Head back to the Windows 10 settings app, and choose Update & security. Then choose Recovery on the left side. Under Advanced startup, choose the Restart now option.

Step 5: 
In the pop-up prompt, choose Use a device. Your USB drive should appear listed. Choose it, and Windows will restart to your USB drive and Windows 11 installer.
![alt text](2.png)

Step 6: 
Once in the Windows 11 installer, select a language, and click Next. Pick the version of  that matches the version of Windows 10 on your PC. and click Next.

Step 7:
Choose the Custom option and choose the drive to  install Windows 11 on. You might have to click the Format button to erase all your files on the drive. When done, select the drive again and click Next.
![alt text](3.png)

Step 8: 
Windows 11 will install to your PC, and you can sit back. You'll then be taken to the out-of-box experience, and will be prompted to set up your PC again.
![alt text](4.png)


2.Install a Text Editor or Integrated Development Environment (IDE):
Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

step 1.
Visit  https://code.visualstudio.com/Download  and select “Download for Widows”.
![alt text](5-1.png)

step 2.
Wait for the download to finish and then head to downloads folder.

step 3.
Click on it initiate the installation process.

step 4.
After the installer opens,it will ask you to accept the terms and conditions of visual studio code.Click on I Accept the agreement  and then click the Next button.
![alt text](6.png)

step 5.
Choose the location data for running the vs code .It will then ask you to browse the location .Then click on the Next button.
![alt text](image.png)

step 6.
Then it will ask to begin the installation setup .Click on the Install button.
![alt text](8.png)

step 7.
This will take about 1 minute.

step 8.
After the installation setup for visual studio code is finished, it will show window below.Tick the checkbox and click Next.
![alt text](9-1.png)

step 9.
Visual studio code window opens successfully .

3.Set Up Version Control System:
Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

step 1
After successfully starting the installer, you should see the Git setup wizard screen. Click      the Next and Finish prompts to complete the installation.

step 2
Create a GitHub Account-- Visit https://github.com  and sign up for a new account .

step 3
Open a git bash  and run the following commands to configure your Git username and email .
$ git config --global user.name "Leah Mathenge"
$ git config --global user.email "wanjirum.leah@gmail.com"

step 4
While still at the git bash, navigate to your project folder using “cd Desktop/myfolder” or create one using “mkdir project_name” then “ cd project_name”

step 5
Initialize ,commit and push the repository to github using:
git init
git add .
git commit -m “My first project”
git push
![alt text](10-1.png)


4.Install Necessary Programming Languages and Runtimes:
Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

step 1
Visit the official python website https://www.python.org/ to download the latest version of python.
![alt text](11.png)

step 2
b)Select the “Windows installer” option and click on the “Download” button. Once the download is complete, run the installer.heck the boxes “Use admin privileges when installing py.exe” and “Add python.exe to PATH” to save the trouble of manual adjustments in the environment variable later.
![alt text](12.png)


c)Follow the on-screen instructions during the preceding stages.Once installation is complete you should see the a message like this:
Verify that the installation is complete using
python -v   on the command prompt.
![alt text](13.png)


5.Install Package Managers:
If applicable, install package managers like pip (Python).
On the command prompt, check whether  pip is installed by executing:
pip –version   since it comes by default after downloading python.


6.Configure a Database (MySQL):
download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Visit https://dev.mysql.com/downloads/installer/ and click on the first download button.
![alt text](14.png)
On the mysql Homepage, click on the “No thanks, just start my download” link to proceed mysql downloading.
![alt text](15.png)
After mysql downloading MySQL.exe file , go to your down	loads folder , find the file and double click to run the installer.
![alt text](16.png)
The installer will instruct you to choose the setup type. For most users , the “Developer Default” is suitable. Click “Next” to proceed.

You will be prompted to install typical MySQL software .The installer can auto-resolve some of issues, but not in this case.
![alt text](17.png)
in the downloads section click, "Execute" to start downloading the content you selected.Click "Next"
![alt text](18.png)
Proceed to 	“Product configuration” > “Type and Networking” > “ Authentication Method” pages by clicking the “Next” button.
Create  a password for the MySQL root user.Ensure it is strong and memorable.Click Next to proceed.
Connect to server: Enter the root password , click “Check” .If it says “Connection Succeed” you have successfully connected to the server.
Once installation is complete , click “Finish” .
![alt text](19.png)
To verify installation, open MySQL  command line client  at your start menu  and login using the root user credentials you set during installation.
7.Set Up Development Environments and Virtualization (Optional):
Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8.Explore Extensions and Plugins:
Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
To install extensions , open vs code,  go to Extensions view( ctrl +shift +X).
Examples of extensions I installed:
Flutter files
Auto close tag
Auto complete tag
C/C++
Code runner
color Highlight
Dart
Django-intellisence
CHALLENGES FACED DURING SETUP AND STRATEGIES DEVELOPED TO OVERCOME THEM

Challenge: Compatibility issues, errors during installation.
Solution: I Followed the official troubleshooting guide provided by Microsoft for common installation and activation issues.
Challenge: Network issues .
 Solution: I used a download manager to ensure the download completes successfully.
Challenge: Extension conflicts or performance issues.
Solution: I checked  user reviews and documentation for each extension to ensure compatibility.
Challenge: Connection errors between my application and the MySQL database. Solution: Ensured MySQL is running and accessible on the correct port (default is 3306).




9. Document Your Setup:
Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
