# java-racingcar-precourse

## 기능 요구 사항
***
### 자동차 이름 입력
- 자동차의 수 n대
- 자동차는 각각 고유의 이름이 있음
- 자동차 이름
    - 쉼표(,)를 기준으로 구분
    - 5자 이하 입력

### 전진할 수 있는 횟수(a) 입력
- 모든 차는 a번의 전진할 수 있는 기회를 얻음
- 전진할 수 있는 기회를 의미하는 a는 사용자에게 직접 입력 받음
- a > 1

### 자동차 경주 전진 조건
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우

### 자동차 경주 과정 출력
- 전진 차수별 실행 결과를 표시
  ```
    pobi : --
    woni : ----
    jun : ---
  ```
### 자동차 경주 결과 출력
- 단독 우승자 안내 문구
    - ``최종 우승자 : pobi``
- 공동 우승자 안내 문구
    - ``최종 우승자 : pobi, jun``

## 프로그래밍 요구사항
***
- JDK 21 버전에서 실행
- indent depth가 3을 넘지 않도록 하기
- 3항 연산자를 쓰기
- 함수는 한 가지 일만 하도록 선언하기
- ``camp.nextstep.edu.missionutils``의 ``Random`` 및 ``Console`` 사용
    - ``pickNumberInRange()``
    - ``readLine()``