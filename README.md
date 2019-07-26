#### Naan Factory 2 Testing

1. First create a new file
###Testing Processes
We need to open a new naan factory 2.

##Testing Processes 
###*Test 1 - Ingredients to Dough*
To make naan, we need wheat flour and water. Define the function and carry out the test:
####Function and Test 1:
def make_dough (arg1, arg2):
    return "dough"
Define 'make_dough' process as a part of 2 arguments and print. The two arguments are 'wheat and water'
print(make_dough("wheat", "water") == "dough")
The above are the function and the test command to successfully implement the function.
###*Test 2 - Baking the Dough*
The next step is to knead the dough and bake it in a heated chamber
As before we define the function and carry out the test:
####Function and Test 2:
def bake_dough (arg1):
    return "naan"
Define 'bake_dough' as part of a single argument and print. The only argument here is dough
print(bake_dough("dough") == "naan")
The above commands have been successful in being tested and have been allocated within the Git Repository
#Git Bash Commands for the Naan Factory 2 Processes
##*What is Git Bash?*
Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. Bash is an acronym for Bourne Again Shell. A shell is a terminal application used to interface with an operating system through written commands.
##*Line Commands in Git Bash for Naan Factory 2*
Step 1 - Know the access point of the drive
- Step 1 - Know the drivepoint access which you have
-      $ pwd -->
       /c/Users/AHirani
   Use cd ~ to find file if it's not shown
- Step 2 - List all directories in that drive (note that 'ls -a' will display the PyCharm queries for Naan Factory 2)
-      $ ls -a
- Step 3 - Access PyCharmProjects and initialise an empty Git Repository
-      $ cd PycharmProjects
       $ git init
- Step 4 - Check Git Status
-      $ git status
- Step 5 - Add and commit the PyCharm processes for Naan Factory 2
-      Since changes aren't committed:
       $ cd NaanFactory2
       $ git add .
       Then commit first save:
       $ git commit -m "First Test Complete"
       $ git add .
       Then commit second save:
       $ git commit -m "Second Test Complete"
- Step 6 - Let Git create the changes in files and insert new data into the Repository
- Step 7 - Confirm Git Status after letting Git add into the repository
-      $ git status
       You will see this message:
       'On branch master nothing to commit, 
       working tree clean'
And there you have it. You have successfully started your Naan Factory 2 and are on your way to understanding Python and Git as well as committing savepoints into a blank Git Repository!
       
Please note: **the README.md (this file) needs to also be committed**
- Step 8: Add and commit the README.md file
-       $ git add README.md
        $ git commit -m "README.md compiled and completed
        $ git add README.md
        $ git commit -m "Added README.md in commit under Git
