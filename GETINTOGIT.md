
#Steps to use the github
Step 1:
Create the github account by using below link
(https://github.com/join?source=header-home) 
and fill all the required feilds and verify the email address.--

Step 2: sign in into your git hub account and create new repository --

step 3: Install Git in your local system --

for Ubuntu use the below command
sudo apt-get install
for cent os by default it will be installed
check and verfy by the git version
git --version
expected output is the version of the git.
step 4 configure the git account
git config --global user.name "your loginname"
git config --global user.email "your email"


create one new directory and go inside the directory 
step 5 initialize the git
git init
step 6 
git remote add origin httpurl 

the http link you can get by web interfacce once you logged into the github select the repository and in the reight corner option will come up t
o clone or download select the option and url will be appeared,copy the url and replace the hhtp link with that without brackets

step 7
 create one file with .md extension and add some content

How to upload the local file to repository??
git add filename
git commit -m "some commit message"
git push origin master
it will prompt the username and password give the creddentials.

