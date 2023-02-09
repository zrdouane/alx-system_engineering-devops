# Shell Permissions

_This repository contains executable files with commands related to permissions._

## ¿How to execute the files?

You must first write to your Terminal `./` Following the name of the file you want to run.

### Example:
```
./name_of_file
```
### :file_folder:- Directories

#|Files|Description
---|:---:|---
*|[README.md](./README.md)| Readme file.
0|[_su_](./0-iam_betty)|  Script that switches the current user to the user betty.
1|[_whoami_](./1-who_am_i)| Script that prints the effective username of the current user.
2|[_groups_](./2-groups)| Script that prints all the groups the current user is part of.
3|[_sudo chown_](./3-new_owner)| Script that changes the owner of the file `hello` to the user `betty`.
4|[_touch_](./4-empty)| Script that creates an empty file called `hello`.
5|[_chmod_](./5-execute)|Script that adds execute permission to the owner of the file `hello`.
6|[_chmod_](./6-multiple_permissions)| Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.
7|[_chmod_](./7-everybody)| Script that adds execution permission to the owner, the group owner and the other users, to the file `hello`.
8|[_chmod_](./8-James_Bond)| Script that sets the permission to the file `hello`.
9|[_chmod_](./9-John_Doe)| Script that sets the mode of the file `hello`.
10|[_chmod_](./100-Star_Wars)| Script that sets the mode of the file `hello` the same as `olleh`’s mode.
11|[_chmod_](./11-lists)| Create a Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12|[_mkdir_](./11-directories_permissions)| Create a script that creates a directory called `dir_holberton `with permissions 751 in the working directory.
13|[_chgrp_](./13-change_group)| Script that changes the group owner to `holberton` for the `file hello`.
14|[_chown_](./14-change_owner_and_group)| Script that changes the owner to `betty` and the group owner to `holberton` for all the files and directories in the working directory.
15|[_chown_](./15-symbolic_link_permissions)| Script that changes the owner and the group owner of `_hello` to `betty` and `holberton` respectively.
16|[_chown](./16-if_only)| Script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.
17|[_telnet_](./100-Star_Wars)| Script that will play the StarWars IV episode in the terminal.
