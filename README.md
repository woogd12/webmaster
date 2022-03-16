# webmaster

## World Wide Web, WWW, W3
+ 인터넷에 연결된 컴퓨터를 통해 사람들이 정보를 공유할 수 있는 전 세계적인 정보 공간을 말함

## Web의 기본 3가지 요소
+ URI (Uniform Resource Identifier)
  + 리소스 식별자 
  + 특정 사이트, 특정 쇼핑 목록 
  + 모든 정보에 접근 할 수 있는 정보 

+ HTTP (Hypertext Transfer Protocol)
  + 어플리케이션 컨트롤
  + GET / POST / PUT / DELETE

+ HTML (Hyper Text Markup Language)
  + 하이퍼미디어 포맷
  + XML을 바탕으로한 범용 문서 포맷
  + 사용자가 알아보기 쉬운 형태로 표현

## REST
+ Representational State Transfer 자원의 상태 전달 - 네트워크 아키텍처
+ Clint, Server : 클라이언와 서버가 서로 독립적으로 분리 되어 있어야 한다.
+ Stateless : 요청에 대해서 클라이언트의 상태를 서버에 저장하지 않는다.
+ Cache : 클라이언트는 서버의 응답을 Cache(임시저장) 할 수 있어야 한다.
+ 계층화 : 서버와 클라이언트 사이에, 방화벽, 게이트웨이, Proxy 등 다양한 계층 형태로 구성이 가능해야 하며, 이를 확장 살 수 있어야 한다.
+ 인터페이스 일관성 : 인터페이스의 일관성을 지키고, 아키텍처를 단순화시켜 작은 단위로 분리하여, 클라이언트, 서버 가 독립적으로 개선 될 수 있어야 한다.
+ Code on Demand(Optional) : 자바 애플릿, 자바스크립트, 플래시 등 특정한 기능을 서버로 부터 클라이언트가 전달받아 코드를 실행 할 수 있어야 한다.
