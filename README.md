Create GIT Repository
Create a new folder, and set up an express project inside it.

Add a .gitignore file, inside which add node_modules/ so that folder is not uploaded.

Inside the folder, from command line

# initialize git
git init
# Add files
git add -A
# Commit your changes
git commit -m "simple hello world server"
Upload to github
git remote add origin https://github.com/championswimmer/ngbc-sample-march19-.git
git push -u origin master