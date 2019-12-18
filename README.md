# test_repo
``` git checkout featureC 
 git add .
 git commit "ble ble"
 git push
```
opening pull request
iterating over git add . / git commit / git push in order to fullfill reviewers points
```
- git checkout master
- git pull
- git checkout branch
- zakładamy że pracujemy tylko my na branchu i jesteśmy up-to-date
- git rebase master
- rozwiązujemy konflikty na poziomie plików
- git add {conflicted_files_resolved}
- git rebase --continue
- git pull --force
```
merge your branch with master on gitbub/bitbucket
its good to refresh update local master repository
```
- git fetch
- git checkout master
- git pull
```
