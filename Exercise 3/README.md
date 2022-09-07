## EXERCICISE 3
#### STEP 1
According to the instruction given, i created 3 groups
* Admin
* support
* Engineering

Using the groupadd command example: groupadd admin.

And after that i added the admin group to sudoers as instructed using the command visudo /etc/sudoers. to edit the sudoers files and add the admin group to sodoers.
#### STEP 2
I created 3 users using the command adduser example: adduser user1. After which i added each of the users to each groups respectively using usermod command example: usermod -G admin user1. 
#### STEP 3
 I then switched to switched to the user in the admin group using sudo su - user1. then i generated the ssh key using ssh-keygen command.

Below are the screenshot of the contents we were told to submit

1. content of  /etc/passwd. 
![passwd img](./etc%2Cpasswd%20content.png "passwd img")

2. content of /etc/group.
![group img](./etc%2Cgroup1.png "group img1")
![group img2](./etc%2Cgroup2.png "group img2")

3. content of /etc/sudoers.
![sudoers img](./etc%2Csudoers.png "sudoers img")

