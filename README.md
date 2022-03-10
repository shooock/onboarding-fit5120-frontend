# How to setup the github for your own laptop
- Install git by using this link: https://git-scm.com/downloads . Git and Git bash should be installed.
- Copy the link https://github.com/ymul0001/onboarding-fit5120-frontend.git
- do `git clone https://github.com/ymul0001/onboarding-fit5120-frontend.git`
- The master repo will be pulled 

# The flow to upload the code to the github
- do `git pull origin master` everytime you want to commit the code
- create a separate branch `git checkout -b [your_branch_name]` to avoid the code being pushed directly to the master branch which will create conflicts (change [your_branch_name] to your desired branch name)
- do `git add -A` to add your code inside the repo
- do `git commit -m "[ur_message]" to commit the code (change [ur_message] to your desired message)
- do `git push origin [your_branch_name]` to push the code (change [your_branch_name] to your newly created branch name)
- create pull requests in Github
