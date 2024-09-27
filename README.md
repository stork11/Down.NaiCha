git checkout --orphan latest
git add -A
git commit -m newest
git branch -D main
git branch -m main
git push -f origin main