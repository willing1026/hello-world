# hello git

### git 명령어 요약

 - clone
 - add
 - commit
 - push


### 이 내용 작성전으로 branch 딸거야

### 브랜치 변경하기
 - 브랜치란: 기존 내용 유지한 채 새로운 내용 추가하고 싶을때 사용
 - 체크아웃: 특정 브랜치(커밋) 으로 돌아가고 싶을 때 사용
 - 소스트리에선 더블클릭만으로 가능

### 병합하기 1
- 헤드 브랜치에 변경사항이 없고
- 병합 대상 브랜치가 헤드로부터 시작된 경우
- 아주 쉽게 병합 가능 = fast forward

### 병합하기 2
- 헤드 브랜치에 추가적인 커밋 있는경우
- 진짜 병합이 필요해 진다
- 충돌이 안나면 좋은데, 충돌이 나면 수정하면 된다

### git 사용법 잘 익혀보자

### 커밋 되돌리기

#### 리셋 사용하기
- 장점: 쉽다
- 단점: 커밋 날아간다, 강제 푸시 필요하다

### 브랜치 만들어서 되돌리기
- 리셋과는 달리 내용이 사라지지 않는다.
- 장점 : 쉽다
- 단점 : 트리가 지저분해진다.
- 두번째 연습

### 리버트 되돌리기용
- 추천서적 : 치믈리에!

<<<<<<< HEAD
### 기타 주의사항
- 코드를 남기려고 주석을 달지 말자!
- 커밋 메시지를 잘 쓰자!
- 한가지 기능 구현이 완료 될때마다 커밋하자
=======

### rebase
- merge처럼 두 브랜치를 합칠때 사용
- 현재 브랜치가 대상 브랜치 위로 올라간다.
- 주의해서 사용!
>>>>>>> # rebase 설명추가
