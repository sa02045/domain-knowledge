# CI(Connecting Information) 연계정보

## CI란 무엇인가?

- 본인확인기관(NICE, KISA등)이 이용자의 주민번호와 본인확인기관간 공유 비밀정보를 이용하여 생성한 정보
- 주민등록번호를 대신하는 **온라인 주민등록번호**라고 생각할 수 있다

## 왜 사용하는가?

- 현행법상 정보통신서비스 제공자들은 본인확인 기관으로 지정받지 않는 이상 이용자의 주민등록번호를 수집ㆍ이용할 수 없다(정보통신망 이용촉진 및 정보보호 등에 관한 법률(정보통신망법) 제23조의2(주민등록번호의 사용 제한))
- 따라서 주민등록번호 대신 CI를 사용하여 이용자를 특정한다.

## 기타 정보

- 주민등록번호 + 비밀번호에 해시함수를 적용하여 생성된다
- 88byte 크기로 숫자 + 대소문자로 구성된다
- 고유한 값으로 서로 다른 본인확인기관에서든 동일한 값이 제공된다.
