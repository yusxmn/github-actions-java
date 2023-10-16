# github-actions-java

Fibonacci 계산하는 자바 프로그램으로서 github actions을 사용하여 자동으로 CI를 구현하였다.
1) github repository에서 코드를 checkout
2) JDK 17 설치 (Amazon Corretto)
3) maven을 사용하여 package 생성(Fibonacci-1.0-SNAPSHOT.jar)
4) maven을 사용하여 단위 테스트
5) Jar 화일 실행
