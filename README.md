# 230822 내용 정리 #

## 기존 정보 삭제 ##

git config --unset (유저네임/이메일)

## git branch ##

git이 존재하는 줄기. git branch (이름)으로 생성


git branch -d (브랜치 이름) : 브랜치 삭제

git switch (브랜치 이름) : 해당 브랜치로 이동 (-사용시 직전 브랜치로 넘어감)

git branch --list : git이 위치한 브랜치 확인 가능

git switch -c (브랜치 이름) : 브랜치 생성과 동시에 그 브랜치로 넘어감

## git merge ##

생성된 브랜치를 메인 브랜치로 합침(동기화)

## git push ##
#### repository에서 생성된 remote 명령어를 통해 깃허브로 푸시될 주소를 설정함 ####

git push -u origin main : github에 내 파일 동기화

 → github에서 repository와 동기화

# github - fork #

다른 사람의 repository를 가져올 수 있음

git clone (HTTPS 주소) 명령어를 통해 원하는 로컬 저장소로 내려받은 후 수정이 가능함