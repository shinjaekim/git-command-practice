# git-command-practice

## git command practice
starting date : 2023.02.08

from now on,
<br>
I will record usage of git command
<Br>
project for git practice will be spring boot project
<br>
and for enhancing english
<Br>
English and Korean will be showed together in this repository

## 기본

> git : 형상 관리, 버전 관리

> head : 마지막 커밋 위치를 가리키는 포인터

1. git init

    로컬의 작업폴더를 깃이 관리하는 폴더로 만든다.

    이 후부터는 해당 폴더를 깃이 추적한다.

2. git add

    변경된 파일을 staging area로 load한다.
    
    추후 stage 관련 명령어와 사용하여 

    현 작업 브랜치에서 급하게 다른 브랜치로 넘어가야 하는 경우 사용하게 된다.

3. git commit

    repository로 commit을 한다.

    추후 push 명령어를 쓰면 remote repository로 변경사항을 적용할 수 있다.

4. git status

    변경된 파일, 스테이징 된 파일들을 쭉 알려준다.

5. git restore

    스테이징 된 파일(add한 파일)을 취소하고 싶다면 이 명령어를 이용하자.

6. git log

    깃의 커밋 목록을 확인할 수 있다.


## intelij

> 인텔리제이에서는 gui로 git 을 제공한다.

툴바에 git 
    commit
    push
    fetch
    pull

## todo
rebase에 대해 알아보기
    hard rebase
    soft rebase
fast forward 알아보기

gui 찾아보고 적용해보기

오늘은 하나

git convention

add. adding something about function
refactor. fix not related to function
fix. fix function things
comment 

rebase and merge
rebase 는 커밋 히스토리의 정렬

merge는 헤더를 바꾼다.

머지는 패스트포워드
리베이스는 커밋정렬

다른 브랜치로 넘어갈 때 스태쉬

리셋 - 하드 소프트.
과거 커밋으로 돌아가.는데 현재의 코드를 날릴 것인가

git add  깃이 추적하는 스테이징
git commit 스냅샷을 생성한다......................
...........,..........................