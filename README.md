# IFocusDevOpsTraining

12/03/2025::
============

Introduction about the all tools 

<img width="846" alt="CI-CD" src="https://github.com/user-attachments/assets/1789ebfa-2809-465e-8dbc-01ad575eeba6" />


13/03/2025::
===============

Taken again 2nd demo of the all teh tools flow

<img width="846" alt="CI-CD" src="https://github.com/user-attachments/assets/cf86fc29-ece1-4fec-9579-dd2f1f61565f" />

What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security

Install Git in you local machine

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine

![image](https://github.com/user-attachments/assets/e33acd91-3c58-4284-8e39-13f3f2b486d3)


GitHub account creation:: for creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image

![image](https://github.com/user-attachments/assets/f0e311c5-629f-4e53-bf3a-3edee944eeff)


Github::Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: storage area of your source code. Create a Repository on GitHub

click Repositories

Enter Repository Name::

![image](https://github.com/user-attachments/assets/a6d6c3c8-8814-45b3-8c39-994e6546470d)

Public:: Anyone on the internet can see this repository.

Private:: You choose who can see and commit to this repository.

Click Create Repository

![image](https://github.com/user-attachments/assets/c592782f-e429-43bb-a064-fbbe24d30c41)

Repository Created SUccessfully with Default branch main

![image](https://github.com/user-attachments/assets/bb4deaf9-ff56-473a-b3e6-46ac0346883e)



14/03/2025::
============

Github Introduction::
===============

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: ::
GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.

Clone repository/Project from github to local machine steps::
=============================================

Fork::Fork means to make a copy of the repository into my own github account
A fork is a copy of a repository

![image](https://github.com/user-attachments/assets/9710696d-1991-4f8d-a66c-bc4ed70d44c3)

Fork done

![image](https://github.com/user-attachments/assets/9d7eeeeb-adb0-4aff-a5a4-78755e99d1c7)

Clone Project and Push Changes to Github Repository::

Go to Code and copy url

![image](https://github.com/user-attachments/assets/cfe0f9a6-e661-4a4c-871f-7a6d84c97f9a)

Go to Local Folder and right click and Open Git Bash here and it will navigate to gitbash

![image](https://github.com/user-attachments/assets/8622a586-526f-41c6-bb5c-3494372e0007)

navigate to gitbash

![image](https://github.com/user-attachments/assets/6a8aab98-73eb-4fc8-bfb2-607297064e75)

Copy Repository URL

![image](https://github.com/user-attachments/assets/19aedccf-571e-4034-b5fc-8d05d442f39d)

Git Commands::

>git clone <repo url>

>git clone https://github.com/parasa7358/spring-petclinic.git
>

>![image](https://github.com/user-attachments/assets/e8b7464b-069e-43ed-b372-86ddd7a730c4)


![image](https://github.com/user-attachments/assets/0590c587-3511-4a80-9de1-52536ec90cef)


>cd <reponame>

>git checkout <branchname>

>git status

>git add --all

>git status

>git commit -m "commit message"

>git push origin

All Steps::

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS
$ git clone git@github.com:parasa7358/spring-petclinic.git
Cloning into 'spring-petclinic'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 10425, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 10425 (delta 0), reused 0 (delta 0), pack-reused 10423 (from 2)
Receiving objects: 100% (10425/10425), 7.67 MiB | 706.00 KiB/s, done.
Resolving deltas: 100% (3935/3935), done.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS
$ cd spring-petclinic/

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (main)
$ git checkout feature/2025.02.24
branch 'feature/2025.02.24' set up to track 'origin/feature/2025.02.24'.
Switched to a new branch 'feature/2025.02.24'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git status
On branch feature/2025.02.24
Your branch is up to date with 'origin/feature/2025.02.24'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git commit -m "This is first commit for this project and updated pom.xml"
[feature/2025.02.24 434fce4] This is first commit for this project and updated pom.xml
 1 file changed, 1 insertion(+)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git push
ssh: Could not resolve hostname github.com: Name or service not known
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   6c05fc9..434fce4  feature/2025.02.24 -> feature/2025.02.24

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/AWS/spring-petclinic (feature/2025.02.24)
$

Screenshot::

![image](https://github.com/user-attachments/assets/1e723036-90a9-4cee-8d31-2746f37f525b)


17/03/2025::
===========


Github branching strategy::
===========================

<img width="846" alt="Untitled" src="https://github.com/user-attachments/assets/406f212d-86de-4283-99f7-f8f823c99baf" />

A GitHub branching strategy is crucial for maintaining an organized workflow in version control. There are different strategies depending on the size of the project, the number of team members, and the desired workflow. Here are some common branching strategies used in GitHub:

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.03.17

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.03.17

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.

cloning references::

![image](https://github.com/user-attachments/assets/87f6ed4a-095b-4faa-854a-7fcdc019f31f)


Generate SSHKeys::

syntax::ssh-keygen -t ed25519 -C "your_email@example.com"

Keys avaibale path and save the key (/c/Users/HP/.ssh/id_ed25519):
![image](https://github.com/user-attachments/assets/c1031abb-57bf-4585-88a9-e1fbb9358621)

![image](https://github.com/user-attachments/assets/ce78114d-1a3f-4adf-a677-c3f26736f6cc)


Please follow below links for more understanding 

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account

Go to -->settings

![image](https://github.com/user-attachments/assets/e6856f23-6d62-4e02-8fb2-05c720542ec3)

Click SSH and GPG Keys

![image](https://github.com/user-attachments/assets/906f1f68-79a8-4920-837f-38f165e5849e)

click New SSH Key

![image](https://github.com/user-attachments/assets/a461189f-f9e1-415c-b52e-c25f6cfaf1d2)

Add new SSH Key and click Add SSH Key

![image](https://github.com/user-attachments/assets/f62d4d90-f588-462b-bf04-54de51e566d8)

Clone Project code using SSH URL::
===============================

>git clone git@github.com:ifocusbatch2/spring-petclinic.git

![image](https://github.com/user-attachments/assets/1b704706-cfe5-4db1-8917-e7ca4c44e35f)

![image](https://github.com/user-attachments/assets/12f6150b-e9e9-4615-9864-4e3424a594dd)

![image](https://github.com/user-attachments/assets/03037e55-f77d-499e-b845-4e775b82afed)

![image](https://github.com/user-attachments/assets/8c5653a0-1427-4b26-968b-cda90c04cc48)


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17
$ git clone git@github.com:ifocusbatch2/spring-petclinic.git
Cloning into 'spring-petclinic'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 10430, done.
remote: Total 10430 (delta 0), reused 0 (delta 0), pack-reused 10430 (from 1)
Receiving objects: 100% (10430/10430), 7.67 MiB | 1.17 MiB/s, done.
Resolving deltas: 100% (3935/3935), done.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17
$ cd spring-petclinic/

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git commit -m "updated pom.xml file"
[main b2e46bf] updated pom.xml file
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 340 bytes | 340.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:ifocusbatch2/spring-petclinic.git
   2aa53f9..b2e46bf  main -> main

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (main)
$ git checkout -b feature/2025.03.17
Switched to a new branch 'feature/2025.03.17'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git status
On branch feature/2025.03.17
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   pom.xml

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git add --all

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git status
On branch feature/2025.03.17
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   pom.xml


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git commit -m "added branch"
[feature/2025.03.17 f393310] added branch
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git push
fatal: The current branch feature/2025.03.17 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature/2025.03.17

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/Ifocus/batch2_17/spring-petclinic (feature/2025.03.17)
$ git push origin feature/2025.03.17
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 302 bytes | 302.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'feature/2025.03.17' on GitHub by visiting:
remote:      https://github.com/ifocusbatch2/spring-petclinic/pull/new/feature/2025.03.17
remote:
To github.com:ifocusbatch2/spring-petclinic.git
 * [new branch]      feature/2025.03.17 -> feature/2025.03.17
