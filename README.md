# java-calculator-precourse

## 기능 요구 사항
1. 쉼표 또는 콜론 :을 구분자로 가지는 문자열을 전달하는 경우에
구분자를 기준으로 숫자의 합을 반환하는 기능
2. 앞에 지정되어 있는 구분자 이외에 커스텀 구분자를 지정할 수 있다.
커스텀 구분자는 문자열 앞부분의 //와 \n 사이에 위치하는 문자를 지정하는 기능.
3. 사용자가 잘못된 값(형식에 맞지 않는 값)을 입력할 경우의 예외 처리

### 예외 세세하게 나누기
1. null 값 여부 확인 || "" 값 여부 확인
2. 구분자와 양수로 구성되어야 함. 구분자는 문자만 가능.

### 내가 더 생각한 기능
1. 커스텀 구분자에서 정규식 메타 문자도 구분자로 가능하게 하기.
2. 요구 사항에 양수가 가능하다고 하였는데, 그러면 소수도 가능해야 하지 않을까 하여 소수도
가능하게 하되, 출력이 소수라면 소수 둘째 자리까지 나오게 함.(정수라면 정수로 출력)