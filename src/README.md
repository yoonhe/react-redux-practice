Redux(state) => 안정성, state 통제 용이

- store 설정(state)
- Action => state를 바꾸는 행동
- Dispatch => Action 실행
- Reducer => Action의 결과로 state를 어떻게 바꿀지 정의

ex) 로그인액션 dispatch시 => isLoggined state를 true로

- 리액트는 리덕스와 별개이다, 그렇기때문에 redux 모듈도 필요하고 리액트와 리덕스를 연결해주기위한 react-redux 모듈도 필요함
- 리덕스의 상태관리 시스템을 리액트에서 사용하기위해 react-redux가 필요함

- ACTION을 통해서만 state 관리가 가능하기때문에 공통 state를 잡아 놓고 Action, reducer를 각자 만드는것이 어떤지?.

[store 쪼개기]

- 너무 한곳에 모여있으면 코드량이 방대해지기 때문에 한단계씩 쪼개준다.(루트 스토어에 모아준다)
