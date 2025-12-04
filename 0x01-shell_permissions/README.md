0x01-shell_permissions
This directory contains the Shell Permissions project for the System Engineering and DevOps course.

The following scripts are included:

0-iam_betty – Switches the current user to the user betty.
1-who_am_i – Prints the effective username of the current user.
2-groups – Prints all the groups the current user is part of.
3-new_owner – Changes the owner of the file hello to the user betty.
4-empty – Creates an empty file called hello.
5-execute – Adds execute permission to the owner of the file hello.
6-multiple_permissions – Adds execute permission to the owner and group owner, and read permission to others for the file hello.
7-everybody – Adds execution permission to the owner, group owner, and all other users for the file hello.
8-James_Bond – Gives no permission to the owner and group, but all permissions to others for the file hello.
9-John_Doe – Sets the mode of the file hello to -rwxr-x-wx.
10-mirror_permissions – Sets the file mode of hello to match olleh.
11-directories_permissions – Adds execute permission to all subdirectories of the current directory.
12-directory_permissions – Creates a directory named my_dir with permissions 751.
13-change_group – Changes the group owner of the file hello to school.

Each script starts with #!/bin/bash and is executable.
