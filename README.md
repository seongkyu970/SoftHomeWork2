# SoftHomeWork2

https://github.com/seongkyu970/SoftHomeWork2.git

[명령어 목록](#명령어-목록)

## config
>  - git을 사용할 때 사용자를 등록하지 못하였고, 확인하지 못하는 상태이다.
> - 사용자가 누군지 다른사람에게 알려주기 위해 이름과 이메일을 셋팅하고 싶다. 
> - 이를 위해 git 명령어 'config'를 사용했다.  
> - 따라서 'config'명령어는 깃과 관련된 설정을 확인하거나 세팅하는 것으로 git config --global user.name 'name' 과 같이 사용되어진다고 정리할 수 있다.
> 그리고 컴퓨터의 모든 git 프로젝트의 이름 및 이메일 정보를 설정하는 --global(사용 하지 않을 경우 현재 이용하고있는 git저장소에 대해서만 설정한다.), 삭제를 위한 --unset 옵션이 자주 사용될 것 같으며 또 다른 옵션으로는  설정 목록을 불러오는 --list, 편집기 변경을위한 --edit 등이 있다.  
![image](https://user-images.githubusercontent.com/67774264/116812879-102ba900-ab8c-11eb-8670-fa9a3d2b8f66.png)   
[Table](#명령어-목록)

## init
> - 현재 문서가 git저장소로 적용되지 않은 상태이다.  
> - 이 문서를 git 저장소로 사용하고 싶다.  
> - 이를 위해 git 명령어 'init'을 사용했다.  
> - 따라서 'init' 명령어는 로컬 디렉토리 하나를 선택해서 git저장소를 적용할 때 사용하는 것으로 정리할 수 있다.
> - 이미 적용되어진 것을 다시 reinitialize 할때도 사용한다. 작업을 할 수없고 저장소로서의 기능만 수행하게하는 --bare 옵션이있다.  
![image](https://user-images.githubusercontent.com/67774264/116811578-1cf8ce80-ab85-11eb-921b-5cbd5a312e98.png)  
[Table](#명령어-목록)


## status
> - git 저장소로 사용되고있는 디렉토리 안에 파일들이 관리(추적)되고 있는지 알고싶다.  
> - 이를 위해 git 명령어 'status'를 사용했다.  
> - 따라서 'status' 명령어는 저장소 작업 트리의 상태를 알고싶을 때 사용하는 것으로 정리할 수 있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116812066-a1e4e780-ab87-11eb-928d-f8b250da957f.png)  
[Table](#명령어-목록)

## add
> - 디렉토리안에 어떤 파일(과제1)이 버전관리가 이루어지지 않는 상태이다.  
> - 이 파일을 git으로 버전관리를 하고싶다.  
> - 이를 위해 git 명령어'add'를 사용했다.  
> - 따라서 'add' 명령어는 git에게 파일을 관리(추적)하라는 것을 명시할 때 사용하는 것으로 정리할 수 있고 기존 중복 디렉터리를 무시하고 추가하는 -f, 수정한 부분에 대해서만 추가하는 -p 등의 옵션이 있다.
> - 버전관리가 되고있는 파일이 수정되어 새로운 버전을 만들기 전에도 'add'명령어를 사용해야한다.  
> ![image](https://user-images.githubusercontent.com/67774264/116811778-0f901400-ab86-11eb-8c5f-70a4fa156d22.png)  
[Table](#명령어-목록)

## commit
> - 수정된 내역을 기록하지 못한 상태이다.
> - 수정된 파일을 추가하고, 수정 사항에 대한 기록을 남기고 싶다.
> - 이를 위해 git 명령어'commit'을 사용했다.
> - 따라서 'commit'명령어는 수정된 사항을 기록하기 위해 'git commit'으로 사용한다고 할 수 있다. 이미 버전관리 되어지고 있는 파일을 add명령어 없이 commit할 수 있는 -a, 커밋 메세지를 넣는 -m 옵션이 많이 사용될 것 같으며 커밋메세지를 수정하는 --amend -m그리고 도움말을 볼 수 있는 --help 옵션이 있다.  
![image](https://user-images.githubusercontent.com/67774264/116839445-64c33880-ac0d-11eb-86d3-7bdd88169d29.png)  
[Table](#명령어-목록)

## log
> - commit 히스토리를 모르는 상태이다.
> - commit된 파일들을 버전별로 보고 싶다.
> - 이를 위해 git 명령어'log'를 사용했다.
> - 따라서 'log'명령어는 commit된 파일들의 히스토리를 보기 위해 'git log'로 사용하는 것으로 정리할 수 있다. 옵션으로는  버전 별로 차이를 보여주는 -p, 저장소 안의 모든 branch를 보여주는 --branches, commit메세지 첫 줄만 보여주는 --oneline 과 같은 옵션들이 많이 사용될 것 같다.  
> ![image](https://user-images.githubusercontent.com/67774264/116819260-48da7b00-abaa-11eb-8d11-27b6adaf70bd.png)   
[Table](#명령어-목록)

## reset --hard
> - commit 을 취소하는 하는 상태이다.( 되돌아 간 이후의 모든 내용을 지워야 한다)
> - git에서 이력을 되돌리고 이후의 모든 내용을 지우고 싶다.
> - 이를 위해 git 명령어'reset --hard'를 사용했다.
> - 따라서 'reset'명령어는 이력을 그 당시로 돌아가기 위해 사용하는 것으로 git reset <옵션> <돌아가고싶은 커밋> 처럼 사용한다고 정리할 수 있다. 그 중 돌아가려는 이력 이후의 모든것을 지우는 --hard가 있으며 되돌아 가지만 이후의 내용과 인덱스가 지워지지않는 --soft옵션도 있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116839630-0ea2c500-ac0e-11eb-9b6f-00ee0766cab1.png)  
[Table](#명령어-목록)

## branch
> - branch(practice)를 생성해야하는 상태이다.(branch는 가지치기 라고 생각하면 된다.)
> - 이를 위해 git 명령어'branch'를 사용했다.
> - 'branch'명령어는 현재 사용되어 지고있는 branch를 확인하거나 새로운 branch를 생성할 때 git branch option 으로 사용된다. 기존 브랜치 명을 변경하는 -m 옵션과 브랜치를 삭제하는 -d옵션이 있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116839720-57f31480-ac0e-11eb-8e76-732134f04788.png)  
[Table](#명령어-목록)

## checkout
> - 사용중인 브랜치(master)에서 다른 브랜치(practice)를 사용해야하는 상태이다. 
> - 다른 브랜치(practice)로 이동하고 싶다.
> - 이를 위해 git명령어 'checkout'을 사용했다.
> - 'checkout'명령어는 브랜치를 이동할 때(태그로 이동할 때)  git checkout BRANCH_NAME 와 같이 사용된다. 신규 브랜치를 생성하고 원격 저장소의 브랜치와 연결하는 -b와 같은 옵션이 있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116839758-748f4c80-ac0e-11eb-8348-557cd4619c57.png)  
[Table](#명령어-목록)

## merge
> - 하나의 브랜치(practice)에서 작업된 commit(merge1)을 다른 브랜치(master)로 가져오지 못한 상태이다.
> - 이를 위해 git명령어 'merge'를 사용한다.
> - 'merge'명령어는 하나 혹은 여러 개의 브랜치를 해드에 통합하는 것으로 git merge BRANCH_NAME 으로 사용한다.다른 브랜치에서 같은 코드를 변경한 이후 머지를 할 경우 conflict 가 발생한다. 머지에 대한 메세지를 남기는 -m 옵션이 있다.  
![image](https://user-images.githubusercontent.com/67774264/116835094-f164fb00-abfb-11eb-9360-934be291961f.png)  
[Table](#명령어-목록)

## remote
> - 현재 로컬 저장소(git 디렉토리)에 대한 원격 저장소(github)가 없는 상태이다.
> - 로컬 저장소에 원격 저장소(github)를 연결시키고 싶다.
> - 이를 위해 git 명령어'remote'를 사용한다.
> - 'remote'는 원격 저장소를 등록하는 명령어로 git remote add NAME 저장소_주소 로 사용할 수 있다. 더 상세히 보여주는 -v, 삭제를 위한 git remote remove NAME 과 같은 옵션이있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116840566-419a8800-ac11-11eb-9302-c8fb49c56894.png)
[Table](#명령어-목록)

## push
> - 로컬저장소(git)에서 작업된 내용이 원격저장소(github)에 보내고 싶은 상황이다.
> - 이를 위해 git 명령어 'push'를 사용한다.
> - 'push'는 로컬에서 수정된 소스를 원격 저장소에 등록하는 명령어로 git push 옵션 로컬_저장소 원격_저장소 로 사용할 수 있다. 원격저장소 주소를 쓰지 않으면 origin에 등록된 서버로 소스 코드를 등록한다.  
>  현재 로컬 저장소의 브랜치와 원격 저장소를 연결시켜 이후 git push만으로도 사용가능하게 하는 -u옵션이 많이 사용될 것 같고, 모든 로컬 브랜치의 변경 사항을 원격 저장소로 등록하는 --all, 로컬 태그의 변경 사항을 등록하는 --tags 옵션이 있다.  
![image](https://user-images.githubusercontent.com/67774264/116836679-6a675100-ac02-11eb-9449-c914da69e444.png)  
[Table](#명령어-목록)

## clone
> - 원격 저장소(github)에 저장된 파일을 git2디렉토리로 가져와야 하는 상황이다.
> - 이를 위해 git2 디렉토리에서 git명령어 'clone'을 사용한다.
> - 'clone'은 다른저장소에 있는 파일을 가져오는 명령어로 git clone 저장소_주소 로컬_디렉토리 로 사용한다. 원격 저장소가 복사한 지역저장소와 동기화 된다.  
> ![image](https://user-images.githubusercontent.com/67774264/116837101-02b20580-ac04-11eb-8207-e85391bcfef1.png)  
[Table](#명령어-목록)

## pull
> - git2 디렉토리 에서 작업하여 수정된 소스가 원격 저장소(github에 push되어있고) 현재 git에서 그 수정된 소스를 가져오지 못한 상태이다.
> - 수정된 소스를 원격 저장소로 부터 가져오고 싶다.
> - 이를 위해 git 명령어 'pull'을 사용한다.
> - 'pull' 명령어는 원격 저장소의 내용을 지역 저장소로 가져오는 명령어로 git pull 저장소_주소 branch로 사용 하며 이미 로컬에 등록된 브랜치에 해당하는 소스를 가져올때는 git pull 로 사용한다.  
> ![image](https://user-images.githubusercontent.com/67774264/116841872-7577ac80-ac15-11eb-928f-7057305b3e6f.png)  
[Table](#명령어-목록)


## tags
> - 소스 코드의 버전을 관리하기 위해 커밋중 어떤 특정한 커밋을 가리키고 싶다. 
> - 이를 위해 git 명령어 'tag'를 사용한다.
> - 'tag'는 특정 커밋 버전에 이름을 붙이기 위해 사용 되어 버전을 알리거나 다시 확인을 위한 용도로 git tag TAG_NAME 커밋해시or브랜치명 으로 사용한다.  
> 태그를 설명하는 -m, 로컬 저장소 태그 삭제를 위한 -d 옵션이 있으며 github releases에 정리된다.
> ![image](https://user-images.githubusercontent.com/67774264/116841917-9fc96a00-ac15-11eb-9e7b-9292fb3c7c8c.png)  
[Table](#명령어-목록)

## rebase
> - 하나의 브랜치(practice)에서 진행된 소스(reb.txt)와 다른 브랜치(master)에서 진행된 소스(reb2.txt)를 합치면서 merge와 달리 히스토리를 일렬로 합치고 싶다.
> - 이를 위해 git 명령어 'rebase'를 사용한다.
> - 'rebase' 는 merge와 최종 결과물은 같지만 히스토리를 정리하기위해 git rebase 로 사용한다.  
> 되돌아갈 시점을 선택하기위한 -i, 되돌린시점을 원상복구하는 --continue 등의 옵션이 있다.  
> ![image](https://user-images.githubusercontent.com/67774264/116842468-a48f1d80-ac17-11eb-9710-e74ec1228c2d.png)  
[Table](#명령어-목록)



## 명령어 목록
| 명령어|사용|
|----------|------|
| [config](#config)|O|
| [init](#init) |O|
|[status](#status)|O|
|[add](#add)| O|
|[commit](#commit)|O|
| [log](#log)|O|
| [reset --hard](#reset---hard)|O|
|[branch](#branch) | O|
|[checkout](#checkout)|O|
| [merge](#merge) |O|
| [remote](#remote) |O|
| [push](#push) |O|
|[clone](#clone) |O|
| [pull](#pull) |O|
| [tag](#tags) |O|
| [rebase](#rebase) |O|
----------------
