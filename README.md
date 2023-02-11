# java-racingcar

자동차 경주 미션 저장소

## 프로그램 정의

사용자가 자동차 목록과 시도 횟수를 입력하면 우승자를 가리는 프로그램

## 구현 기능 목록
- [x] 자동차 목록을 입력 받는다.
- [x] 시도 회수를 입력 받는다.
- [x] 입력값을 기준으로 자동차 목록을 생성한다.
- [x] 자동차 이동 여부를 판단한다.
- [x] 자동차를 움직이게 한다.
- [x] 최종 우승자를 판단한다.
- [x] 최종 우승자를 출력한다.
- [x] 자동차의 현재 위치를 출력한다.

## 인풋 구현
- [x] 참여하는 자동차의 이름을 ","로 구분하여 입력한다
- [x] 게임의 총 진행 회수를 입력한다

## 아웃풋 구현
- [x] 각 게임 회차마다 참여 자동차의 위치 정보를 출력한다
- [x] 모든 게임이 종료된 후 최종 위치가 가장 많은 자동차를 우승자로 선정하여 출력한다. 이 때 우승자는 다수일 수 있다.

## 검증 처리
- [x] 자동차 이름은 1~5자 이내로 입력해야 한다
- [x] 시도 횟수는 상한선이 없지만 0을 입력할 수 없다

---
# 수정 사항 목록
## 기능
- [x] Car와 위치를 분리하는 방법과 그렇지 않은 방법의 장단점을 고민해보고 그에 맞게 수정한다.
- [x] 상수는 해당 역할(책임) 클래스에 위치하도록 한다.
- [x] 역할에 맞는 네이밍을 고민하고, 코드가 보다 잘 읽힐 수 있도록 공백 추가를 고려한다.
- [x] InputView, OutputView 의 호출을 한 곳에서 진행한다.
- [ ] input Validation 추가

## 테스트
- [ ] Car Test 수정
- [ ] Cars Test 작성
- [ ] GamePlay Test 수정
- [ ] CarFactory Test 수정