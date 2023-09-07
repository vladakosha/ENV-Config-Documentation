# Enviroment Configurations

Paragraph explain what this documentation is as what it contains

## Termainal commands

1. Print working directory
   ```bash
   pwd
   ```
2. Home directory
   ```bash
   cd
   ```
3. Change directory
   ```bash
   cd <directory name>
   ```
4. Move one folder back
   ```bash
   cd ..
   ```
5. Move more folders back with /
   ```bash
   cd ../.. 
   # etc
   ```
6. Shows a list of files
   ```bash
   ls
   ```
7. Shows hidden files
   ```bash
   ls -a
   ```
8. Create a folder
   ```bash
   mkdir <nameDir> 
   # few folders with space b/n names
   ```
9. Create a file
   ```bash
   touch <name.formate>
   ```
10. Delete file
   ```bash
   rm <name>
   ```
11. Delete folder
   ```bash
   rm -r <name>
   ```
12. Delete full folder
   ```bash
   sudo rm -r <name>
   # follow instractions
   ```
13. Copy file/directory
   ```bash
   cp <fileName/dirName> <dirName>
   ```
14. Autofill
   ```bash
   # start to tape name of dir/file and press TAP
   ```
15. Open file in Terminal
   ```bash
   nano <name>
   ```
16. Move file/directory to a folder
   ```bash
   mv <file/dir> <dir>
   ```
17. Rename file 
   ```bash
   mv <oldName> <newName>
   ```
18. Open coded in VSC
   ```bash
   code .
   # to open file write code <name>
   ```
19. Clean Terminal
   ```bash
   clear 
   ```
20. Put text inside file
   ```bash
   echo <fileName> 
   cat >> <fileName> 
   ```
21. Preview of text
   ```bash
   cat <name>
   ```


## Git Commands

1. Initialize Git repo
   ```bash
   git init
   ```
2. Clone repo
   ```bash
   git clone [url]
   ```
3. Shows modified files in current dir
   ```bash
   git status
   ```
4. Add files
   ```bash
   git add .
   # for all files, for one <name of file>
   ```
5. Commit content to the repo
   ```bash
   git commit -m "description"
   ```
6. Push updates
   ```bash
   git push origin <nameOfTheBranch>
   ```
7. Create a branch and switch branch
   ```bash
   git checkout -b <new branch name>
   ```
8. List of yours branches
   ```bash
   git branch
   ```
9. Shows all commits in branch history
   ```bash
   git log
   ```
10. Pull commits from tracking branch
   ```bash
   git pull
   ```
11. Delete branch
   ```bash
   git branch -d <name>
   # switch to main before
   ```