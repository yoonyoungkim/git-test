# Git Test

git fetch, rebase test

1. develop 에서 pull --rebase 로 (git fetch + git rebase origin/develop)을 한다.

```shell
# git pull default option
$ git config pull.rebase true # 변경
$ git config -l # 확인
```

```shell
# pull 대신 아래 옵션 중 하나 사용하기
$ git pull --rebase
$ git rebase origin/develop
```
   
2. develop 에서 브랜치(feature)를 만들어 작업하고 develop 에 rebase 하여 merge 한다.

squash - local1
squash - local2
squash - local3

remote squash1
