모던 자바 인 액션
===============

CHAPTER 2 동작 파라미터화 코드 전달하기
CHAPTER 3 람다 표현식
CHAPTER 4 함수형 데이터 처리
CHAPTER 5 스트림 활용
CHAPTER 6 스트림으로 데이터 수집
CHAPTER 7 병렬 데이터 처리와 성능
CHAPTER 8 컬렉션 API 개선
CHAPTER 9 리팩토링, 테스팅, 디버깅
CHAPTER 10 람다를 이용한 도메인 전용 언어
CHAPTER 11 null 대신 Optional 클래스
CHAPTER 12 새로운 날짜와 시간 API
CHAPTER 13 디폴트 메서드
CHAPTER 14 자바 모듈 시스템
CHAPTER 15 CompletableFuture와 리액티브 프로그래밍 컨셉의 기초
CHAPTER 16 CompletableFuture : 안정적 비동기 프로그래밍
CHAPTER 17 리액티브 프로그래밍
CHAPTER 18 함수형 관점으로 생각하기
CHAPTER 19 함수형 프로그래밍 기법
CHAPTER 20 OOP와 FP의 조화 : 자바와 스칼라 비교
CHAPTER 21 결론 그리고 자바의 미래


### Make sure to have JDK8 installed
The latest binary can be found here: http://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html

$ java -version

java version "1.8.0_05"
Java(TM) SE Runtime Environment (build 1.8.0_05-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.5-b02, mixed mode)


You can download a preview version here: https://jdk8.java.net/

### Compile/Run the examples
Using maven:

$ mvn compile

$ cd target/classes

$ java lambdasinaction/chap1/FilteringApples


Alternatively you can compile the files manually inside the directory src/main/java

You can also import the project in your favorite IDE:
    * In IntelliJ use "File->Open" menu and navigate to the folder where the project resides
    * In Eclipse use "File->Import->Existing Maven Projects" (also modify "Reduntant super interfaces" to report as Warnings instead of Errors
    * In Netbeans use "File->Open Project" menu