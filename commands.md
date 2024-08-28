https://www.codecademy.com/article/command-line-commands

# command lines 

- is a text interface
- allows navigation files and folders
- 
- 


-----

https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line


- commands ae use in the terminal
- 
- Navigate your computer's file system along with base-level tasks such as create, copy, rename, and delete:
Move around your directory structure: cd
Create directories: mkdir use on linux
Create files (and modify their metadata): touch
Copy files or directories: cp
Move files or directories: mv
Delete files or directories: rm
Download files found at specific URLs: curl
Search for fragments of text inside larger bodies of text: grep
View a file's contents page by page: less, cat
Manipulate and transform streams of text (for example changing all the instances of <div>s in an HTML file to <article>): awk, tr, sed


https://www.youtube.com/watch?v=tpUyBbD4LQE

## Touch

touch command is the easiest way to create a new empty files
used to change the timestamps on existing files and directories
### create file
syntax 

touch file1 file2 file3

### modify timestamps

file id an important time in the file's history

* acces time - the last time the file was read
* modification time - the last time the contents of the file were modified
* change time - the last time the file metadata was changed.
* 
to locate the history need to use command stat follow by file name
syntax

stat file1 - this id the file with access time mod and chang

Once you finish you can modify it by using 
syntax
touch -m file 1
touch -a file 2

touch can be used to change access and modication time individally
-m is used to change the modification time and -a optonn is used to change the access time
touch -a file 2
stat file 1
touch -m 
state file 1

touch -c fileName

`-c` ,`-d` option in `touch` Command
This is used to update access and modification time.

Syntax:

touch -c-d fileName


)`-d` ” ” option in `touch` Command
This command is used to change only modification date.

touch -d "17 Mar 2023" Geek.txt

)`-r` option in `touch` Command for Copying Timestamps from Another File
This command is used to use the timestamp of another file. Here Doc2 file is updated with the time stamp of File 1.

Syntax:

touch -r second_file_name first_file_name


# similar command for creating files are 

cat
>
vim
