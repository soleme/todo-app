TodoTemplate
 - 화면을 가운데에 정렬시켜 주며, 앱 타이틀(일정관리)를 보여준다.
   children으로 내부 JSX를 props로 받아 와서 랜더링

TodoInsert
 - 새로운 항목을 입력하고, 추가할수 있는 컴포넌트
   state를 통해 인풋의 상태를 관리

TodoListItem
 - 각 할일 항목에 대한 정보를 보여주는 컴포넌트
   todo 객체를 props로 받아와서 상태에 따라 다른 스타일의 UI를 보여줌

TodoList
 - todos 배열을 props로 받아 온 후, 이를 배열 내장 함수 map을 사용해서
   여러개의 TodoListItem 컴포넌트로 변환하여 보여줌

