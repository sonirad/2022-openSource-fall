## 2022-openSource-fall
서강대학교 게임&amp;평생교육원 오픈소스 이해 겨울학기 강의
vim 리눅스 커맨드 라인 기초
/ 모르면 실습이 불가능한 기초 커맨드라인 3가지
1. pwd: print working directory
2. ls: list
3. cd: change directory
vim 에디터
  vim oll.txt // oll.txt 파일 vim으로 열기
- 파일을 처음에 열면 명령모드로 진입한다.
- 입력 하려면, 입력모드로 진입해야함
   -키보드에서 i누르기
- 명령모드 진입은 키보드 esc키 누르기
   - 저장하기(write) --> :w
   - 나오기(quit) --> :q
   - 저장하기 나오기 --> :wq

#day03
깃 버전 관리
깃과 깃허브 차이점
vcs, version control system..

깃과 깃허브의 차이점
깃허브는 깃이라는 기술을 기반으로 만든 플랫폼이다
깃허브에서 만들었는데 마이크로소프트가 인수

#day05
깃 커밋은 작을 수록 좋다.
커밋은 논리적 변경이 있을 때 만든다.
커밋은 독립적 버전을 나타내는 스냅샷이다.

#day06
스테이징 영역
 - 커밋의 포함시킬 변경분(단위)만 불리는 영역.
  - 스테이지의 뜻 영역.
- 스테이징 역역을 잘 활용하여 커밋을 만들 수 있음.
- 깃 이그노어 추가
#day07
중간고사 내용 정리
 - 기본적으로 알아야 하는 명령어
  - pwd, cd, ls
 - vim 사용법
  - 명령모드와 입력모드의 차이, 어떻게 각 모드로 전환라는지
  - 명령모드에서 저장하고 빠져나오는 방법
 - 버전관리를 사용하는 이유
  - 3가지
 - 깃과 깃허브 차이
 - 저장소와 일반 디렉터리의 차이
  - 저장소 만들때 쓰는 명령어(git init)
 - 커밋 로그를 보고 싶을 때 치는 명령어
 - 커밋은 언제 만들었는가
 - HEAD의 정의 : 현재 체크아웃한 브렌치의 가장 최신 커밋을 가리키는 명령어
 - 현제 상태를 확인하는 명령어(git status)
 - 스테이징 영역에 왜 존재하는지
 - 원하는 파일을 스테이징 영역에 올릴 때 쓰는 명령어
 - 커밋 메시지가 "abc"인 커밋을 만들고 싶을 때 어떻게 하나?
  - git commit -m "abc"
  - git commit 하고 엔터친 후, abc 입력
 - .gitignore파일의 역할
 - 브랜치는 언제 만드는가?