# shell_script


Shell script for delete multiple users on linux 


#!/bin/bash

# Create a list of users to delete
users=("user1" "user2" "user3")

# Loop through the list of users and delete them
for i in "${users[@]}"
do
  userdel -r $i
done
