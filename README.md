# Hello coders! :wave:
## It's HacktoberFest and GAWDS :heart: Open Source

![Image](/assets/git.jpg)

### Let's help you submit your first Pull Request.

Once your pull request is being merged, your profile will be visible in the Submissions section of this page. For this exercise you'll be adding a new entry to the source code of this website with your profile details. Excited?  let's begin! :sparkles:
## Step 1
Goto the GitHub repository of this project and fork the project to your account. Click on the fork button on the top right corner of the repository page to do it. Once done, GitHub will take you to the forked copy in your account.
<br/>
## Step 2
Clone the forked repository to your local machine. Click on the big green button saying "Clone or download" and copy the https url of your repository. Fire up the terminal (on linux systems ctrl+alt+t. on Windows open the Git-bash ) navigate to your desired directory and type the following command. Replace the link with the clone URL of your repository and hit Enter.

`git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME_HERE `

## Step 3
Let's start working on the changes required now! First cd into the cloned folder by typing the following command.
`cd YOUR_REPO_NAME_HERE`

Now, Before jumping in to the code, make sure you're working on a different branch and not in master. To create a new branch, from the terminal inside your current project directory type the following command. 

`git branch YOUR_BRANCH_NAME_HERE`

You can give any name to your branch which describes the purpose of the branch.
Once you have created the new branch we'll change the current branch from master to your newly created branch. 

## Step 4
In your  file manager/terminal navigate to the downloaded repo.Create a directory  profiles under it and create a new .md file with your username as the filename
It should look like YOUR_USER_NAME.md eg: sagewhocodes.md
Open this file in your favourite editor and fill the details as below in the frontmatter of the markdown file.

YOUR_USER_NAME.md
---
username: YOUR_USER_NAME<br/>
fullname: YOUR_FULL_NAME
---
Donot forget that the hyphens "---" are also part of the file. Once you finish adding the content, save the file.

## Step 5
Commit the changes with a suitable commit message :heavy_check_mark: . First we need to stage all the changes we made. Open the terminal inside the project directory and execute following commands.<br/>
`git add .`

The above command stages all the changes, now lets commit it with a suitable message.
`git commit -m "YOUR_COMMIT_MESSAGE"`

## Step 6
Let's push the changes to your repository! :arrow_up: execute the following command to push all the changes to the forked copy in your GitHub account.<br/>
`git push -u origin YOUR_BRANCH_NAME`

## Step 7
Now, open your web browser and goto the original repository on GitHub. If your changes has been pushed to your forked copy, You'll be able to see an option saying "New Pull Request" in the original repository. Click on the option, one next page choose the master branch of the main repo against your created-branch name ( choose your branch name we created and not master). the click on create pull request. 
Once you fill in the commit message and comment click on submit pull request.
and you are all done!  
Wait for a reviewer to review your file and merge it to the master. Once its been successfully merged, your profile will be visible in the submissions tab. 

### Congratulations You Have succesfully submitted your first Pull Request :tada: :tada:
