# submodule_ssh

submodule test with ssh.

echo "# submodule_ssh" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git submodule add git@github.com:watarium/cocoon_drop.git cocoon

git push -u origin main
