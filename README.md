# _CommandGit
Git _Command

$ git branch -> 로컬 branch 확인  
$ git branch -r 서버 branch 확인  
$ git checkout -b 브랜치명 브랜치를 만들고 바로 이동  
$ git branch -d(D) test 브랜치 삭제  
$ git status 현재상태(머지나 추가사항) 확인  
$ git add 경로 에러를 해결하고 추가하여 에러해결  
$ git stash 임시저장  
$ git stash pop 임시저장한파일 불러오기  
$ git remote prune origin 깃랩에서 삭제한거 서버와 동기화  
$ git push origin :브랜치네임 서버에서 삭제하기  
$ git remote  
$ git push origin dev  
$ git config http.postBuffer 104857600 git오류시 해결  
$ git merge --squash dev  
$ git merge --no-ff feature- : 새로운 가지 따서 merge(관리상 용이)  
$ git clone 주소  
$ git remote set-url origin 주소 : gitlap 저장소 변경시 설정  
$ git remote -v : gitlap 저장소 주소 확인  
  
// 고아 브랜치 만드는 방법  
$ git checkout master  
$ git checkout --orphan c_YYMMDD_CAMPAIGNNAME  
$ git rm -rf .  
$ git push origin c_YYMMDD_CAMPAIGNNAME  

// 자주 쓰는 명령어  
$ git remote add origin "주소"  
$ git remote -v  
$ git push -f origin master : 원격저장소도 master고 로컬저장소도 master인데 원격저장소에 이력안남을때 로컬에서 강제 푸쉬   

출처: https://webclub.tistory.com/317 [Web Club]  
