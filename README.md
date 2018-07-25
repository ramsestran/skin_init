
how to use:

1. make a new project folder on local
2. create a new repository of the project on git
3. sync the local and the remote one, name this remote repo: 'origin'.('git init -> git add * -> git commit -m "first commit" -> git remote add origin [repo_link] -> git push origin master')
4. add skin_init (this repo) as new remote repo of the new project, name it: 'init' ('git remote add init [repo_link]')
5. pull code from skin_init to local.('git pul init master')
6. push the new code to origin repo.('git push origin master')
7. (optional) remove the init repo.('git remote remove init')

