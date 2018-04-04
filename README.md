#Deployment keys
1. Generate ssh keys with `ssh-keygen -q -t rsa -N '' -f repo-key` which will give you repo-key and repo-key.pub files.
2. Add repo-key.pub to your repository deployment keys.
3. On GitHub, go to [your repository] -> Settings -> Deploy keys