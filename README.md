# SpringBootUpAndRunning: Spring-Boot Version 3

# 2024.1.28 Update
롬복 디펜던시에 업데이트가 필요해서 스프링 애플리케이션 구동이 안 되는 것을 확인했습니다. 4, 6, 8 브랜치에 업데이트를 했지만, 혹시 다른 브랜치에서 스프랭 앱 구동이 안되면, 롬복 최신 버전을 설치해주세요. 
그리고 맥북 M 시리즈 쓰시는 분 중에 아래 관련 오류가 발생하면, 다음 디펜던시를 추가해주세요.

'Unable to load io.netty.resolver.dns.macos.MacOSDnsServerAddressStreamProvider, fallback to system defaults. This may result in incorrect DNS resolutions on MacOS. Check whether you have a dependency on 'io.netty:netty-resolver-dns-native-macos'. Use DEBUG level to see the full stack: java.lang.UnsatisfiedLinkError: failed to load the required native library'

```
<dependency>
	<groupId>io.netty</groupId>
	<artifactId>netty-all</artifactId>
</dependency>
```
--------------------------

SpringBootUpAndRunning
SpringBootUpAndRunning 한글번역책 실습코드

원본 실습코드 https://github.com/mkheck/SpringBootUpAndRunning (SpringBoot 2.4, Java 11)

번역판 실습코드는 SpringBoot 3.0.2와 Java 17 로 구성되어있습니다.

실습 중 질문이 있으면 dev[at]syoh.net 혹은 jungdaesuh1221[at]gmail.com 이메일 주시면 감사하겠습니다. 


### book-spring-boot-up-and-running

### 처음부터 배우는 스프링 부트

[교보문고 바로가기](https://product.kyobobook.co.kr/detail/S000201866534)

<img src="https://contents.kyobobook.co.kr/sih/fit-in/458x0/pdt/9791169210966.jpg" width="500">

#### 목차
- Chapter 1. 스프링 부트
- Chapter 2 도구 선택 및 시작
- Chapter 3 첫 번째 REST API
- Chapter 4 데이터베이스 액세스
- Chapter 5 애플리케이션 설정과 검사
- Chapter 6 데이터 파고들기
- Chapter 7 스프링 MVC로 만드는 애플리케이션
- Chapter 8 프로젝트 리액터와 스프링 웹플럭스를 사용한 리액티브 프로그래밍
- Chapter 9 프로덕션을 위한 애플리케이션 테스트
- Chapter 10 애플리케이션 보안
- Chapter 11 애플리케이션 배포
- Chapter 12 리액티브로 더 깊이 들어가기
