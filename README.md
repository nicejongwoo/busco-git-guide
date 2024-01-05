# Git과 GitHub

## What

**사전적 정의**  

- [ ] Git: 무료 오픈소스 분산 버전 관리 시스템  
- [ ] GitHub: 깃 저장소 호스팅을 지원하는 웹 서비스

## Who

- [ ] 개발과 관련된 모든 직군 또는 개발을 하는 모든 사람  

## When

- [ ] Git: 혼자서 개발을 진행할 때  
- [ ] GitHub: 여러사람이 동시에 개발을 진행할 때  

## Where

- [ ] Git: 본인의 PC, 즉 로컬 환경  
- [ ] GitHub: PC가 있고, 인테넷이 연결되는 환경 어디든

## Why

- [ ] Git: 여러 이슈를 동시에 해결할 때 버전을 관리하기 위해  
- [ ] GitHub: 다른 개발자와 협업을 위해  

## How

### Git 설치  

**Windows**  

- [ ] 다운로드: https://git-scm.com/downloads  
- [ ] .exe 파일 실행
- [ ] 기본 설정으로 설치 진행
- [ ] 설치 완료 확인
  - [ ] 터미널 실행: Win + r -> cmd | 명령프롬프트 검색  
  - [ ] 다음 명령어 입력하여 버전이 나오면 정상적으로 설치 완료  `git --version`  
    ![Alt text](img/image-1.png)  

**Mac(with Homebrew)**  
- [ ] 직접 다운로드: https://git-scm.com/downloads  
- [ ] homebrew를 통한 설치: `brew install git`  

### Git 명령어
- [ ] `git init`
- [ ] `git clone`
- [ ] `git status`
- [ ] `git add .`
- [ ] `git commit -m "commit message"`
- [ ] `git push origin main`
- [ ] `git pull origin main`
- [ ] `git fetch`
- [ ] `git fetch --all --prune`
- [ ] `git checkout -b feature`
- [ ] `git switch feature`
- [ ] `git rebase -i HEAD~2`
- [ ] `git stash`
- [ ] `git stash apply @stash{0}`
- [ ] `git stash drop @stash{0}`
- [ ] `git merge`
- [ ] `git merge --squash`
- [ ] `git cherry-pick hash`
- [ ] `git log --graph --all`
- [ ] `git reflog`

### Git gui 툴 사용하기

**gitk**
- [ ] 윈도우 용은 git 설치하면 자동으로 설치됨
- [ ] 맥용 git gui 툴 설치
  - [ ] `brew update`
  - [ ] `brew install git-gui`
  - [ ] `gitk --all`

**git kraken**  
- [ ] 윈도우용, 맥용 다운로드: https://www.gitkraken.com/
- [ ] 맥 설치: `brew install --cask gitkraken`

**intellij**   
git log
- [ ] 윈도우: ctrl + 9
- [ ] 맥: cmd + 9

git commit
- [ ] 윈도우: ctrl + 0
- [ ] 맥: cmd + 0
