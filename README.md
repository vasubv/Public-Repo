This is a public repository

1. Setting JENKINS Build Trigger in EST
TZ=Canada/Eastern

2. In this setting Jenkins will read GIT, every 2 minutes 
H/2 * * * * 

3. In this setting, Jenkins will read GIT, once every 2H at 45 minutes past the H between 9:00 H & 16:00 H, between days 1 to 5
45 9-16/2 * * 1-5

4. It will type the contents of this file in the Jenkins console ...
