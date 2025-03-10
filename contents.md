
# [Part 1 스프링 부트 도전하기](https://github.com/simpleego/SpringBoot/blob/main/Part%201%20%EC%8A%A4%ED%94%84%EB%A7%81%20%EB%B6%80%ED%8A%B8%20%EB%8F%84%EC%A0%84%ED%95%98%EA%B8%B0.md)
# [Part 2 Spring MVC/JPA/Thymeleaf 연습](https://github.com/simpleego/SpringBoot/blob/main/Part%202%20Spring%20MVC_JPA_Thymeleaf%20%EC%97%B0%EC%8A%B5.md)
# [Part 3 N:1(다대일 관계) 처리하기](https://github.com/simpleego/SpringBoot/blob/main/)
# [Part 4 M:N(다대다) 관계와 파일 업로드 처리](https://github.com/simpleego/SpringBoot/blob/main/)
# [Part 5 Spring Security를 이용한 로그인 처리](https://github.com/simpleego/SpringBoot/blob/main/)

# 전체 목차 

    첫째 날(Day 1)

    CLASS 01 스프링 프레임워크 시작하기

    1.1 개발 환경 구축

    1.1.1 JDK 설치

    1.1.2 이클립스 설치

  1.1.3 톰캣 서버 설치 및 이클립스 연동

  1.1.4 데이터베이스 구축

  1.1.5 STS(Spring Tool Suite) 플러그인 설치

  1.2 실습 프로젝트 생성

  1.2.1 프로젝트 생성

  1.2.2 프로젝트 설정 변경


  CLASS 02 프레임워크 개요

  2.1 프레임워크 개념

  2.1.1 프레임워크의 등장 배경

  2.1.2 프레임워크의 장점

  2.1.3 자바 기반의 프레임워크

  2.2 스프링 프레임워크

  2.2.1 스프링 탄생 배경

  2.2.2 스프링 프레임워크의 특징

  2.3 IoC(Inversion of Control) 컨테이너

  2.3.1 결합도(Coupling)가 높은 프로그램

  2.3.2 다형성 이용하기

  2.3.3 디자인 패턴 이용하기


  CLASS 03 스프링 컨테이너 및 설정 파일

  3.1 스프링 IoC 시작하기

  3.1.1 스프링 설정 파일 생성

  3.1.2 스프링 컨테이너 구동 및 테스트

  3.1.3 스프링 컨테이너의 종류

  3.2 스프링 XML 설정

  3.2.1 〈beans〉 루트 엘리먼트

  3.2.2 〈import〉 엘리먼트

  3.2.3 〈bean〉 엘리먼트

  3.2.4 〈bean〉 엘리먼트 속성


  CLASS 04 의존성 주입

  4.1 의존성 관리

  4.1.1 스프링의 의존성 관리 방법

  4.1.2 의존성 관계

  4.2 생성자 인젝션 이용하기

  4.2.1 다중 변수 매핑

  4.2.2 의존관계 변경

  4.3 Setter 인젝션 이용하기

  4.3.1 Setter 인젝션 기본

  4.3.2 p 네임스페이스 사용하기

  4.4 컬렉션(Collection) 객체 설정

  4.4.1 List 타입 매핑

  4.4.2 Set 타입 매핑

  4.4.3 Map 타입 매핑

  4.4.4 Properties 타입 매핑


  CLASS 05 어노테이션 기반 설정

  5.1 어노테이션 설정 기초

  5.1.1 Context 네임스페이스 추가

  5.1.2 컴포넌트 스캔(component-scan) 설정

  5.1.3 @Component

  5.2 의존성 주입 설정

  5.2.1 의존성 주입 어노테이션

  5.2.2 @Autowired

  5.2.3 @Qualifier

  5.2.4 @Resource

  5.2.5 어노테이션과 XML 설정 병행하여 사용하기

  5.3 추가 어노테이션


  CLASS 06 비즈니스 컴포넌트 실습 1

  6.1 BoardService 컴포넌트 구조

  6.2 Value Object 클래스 작성

  6.3 DAO 클래스 작성

  6.3.1 드라이버 내려받기

  6.3.2 JDBC Utility 클래스

  6.3.3 DAO 클래스 작성

  6.4 Service 인터페이스 작성

  6.5 Service 구현 클래스 작성

  6.6 BoardService 컴포넌트 테스트

  6.6.1 스프링 설정 파일 수정

  6.6.2 클라이언트 작성 및 실행


  CLASS 07 비즈니스 컴포넌트 실습 2

  7.1 UserService 컴포넌트 구조

  7.2 Value Object 클래스 작성

  7.3 DAO 클래스 작성

  7.4 Service 인터페이스 작성

  7.5 Service 구현 클래스 작성

  7.6 UserService 컴포넌트 테스트

  7.7 어노테이션 적용


  둘째 날(Day 2)

  CLASS 01 스프링 AOP

  1.1 AOP 이해하기

  1.2 AOP 시작하기

  1.2.1 비즈니스 클래스 수정

  1.2.2 AOP 라이브러리 추가

  1.2.3 네임스페이스 추가 및 AOP 설정

  1.2.4 테스트 및 결과 확인


  CLASS 02 AOP 용어 및 기본 설정

  2.1 AOP 용어 정리

  2.1.1 조인포인트(Joinpoint)

  2.1.2 포인트컷(Pointcut)

  2.1.3 어드바이스(Advice)

  2.1.4 위빙(Weaving)

  2.1.5 애스팩트(Aspect) 또는 어드바이저(Advisor)

  2.1.6 AOP 용어 종합

  2.2 AOP 엘리먼트

  2.2.1 〈aop:config〉 엘리먼트

  2.2.2 〈aop:pointcut〉 엘리먼트

  2.2.3 〈aop:aspect〉 엘리먼트

  2.2.4 〈aop:advisor〉 엘리먼트

  2.3 포인트컷 표현식


  CLASS 03 어드바이스 동작 시점

  3.1 Before 어드바이스

  3.2 After Returning 어드바이스

  3.3 After Throwing 어드바이스

  3.4 After 어드바이스

  3.5 Around 어드바이스


  CLASS 04 JoinPoint와 바인드 변수

  4.1 JoinPoint 메소드

  4.2 Before 어드바이스

  4.3 After Returning 어드바이스

  4.4 After Throwing 어드바이스

  4.5 Around 어드바이스


  CLASS 05 어노테이션 기반 AOP

  5.1 어노테이션 기반 AOP 설정

  5.1.1 어노테이션 사용을 위한 스프링 설정

  5.1.2 포인트컷 설정

  5.1.3 어드바이스 설정

  5.1.4 애스팩트 설정

  5.2 어드바이스 동작 시점

  5.2.1 Before 어드바이스

  5.2.2 After Returning 어드바이스

  5.2.3 After Throwing 어드바이스

  5.2.4 After 어드바이스

  5.2.5 Around 어드바이스 설정

  5.2.6 외부 Pointcut 참조하기


  CLASS 06 스프링 JDBC

  6.1 스프링 JDBC 개념

  6.2 JdbcTemplate 클래스

  6.3 스프링 JDBC 설정

  6.3.1 라이브러리 추가

  6.3.2 DataSource 설정

  6.3.3 프로퍼티 파일을 활용한 DataSource 설정

  6.4 JdbcTempate 메소드

  6.4.1 update( ) 메소드

  6.4.2 queryForInt( ) 메소드

  6.4.3 queryForObject( ) 메소드

  6.4.4 query( ) 메소드

  6.5 DAO 클래스 구현

  6.5.1 첫 번째 방법 : JdbcDaoSupport 클래스 상속

  6.5.2 두 번째 방법 : JdbcTemplate 클래스 〈bean〉 등록, 의존성 주입


  CLASS 07 트랜잭션 처리

  7.1 트랜잭션 네임스페이스 등록

  7.2 트랜젝션 관리자 등록

  7.3 트랜잭션 어드바이스 설정

  7.4 AOP 설정을 통한 트랜잭션 적용

  7.5 트랜잭션 설정 테스트


  셋째 날(Day 3)

  CLASS 01-02 Model 1 아키텍처로 게시판 개발

  1.1 Model 1 아키텍처 구조

  1.2 로그인 기능 구현

  1.3 글 목록 검색 기능 구현

  1.4 글 상세 기능 구현

  1.5 글 등록 기능 구현

  1.6 글 수정 기능 구현

  1.7 글 삭제 기능 구현

  1.8 로그아웃 기능 구현


  CLASS 03 Model 2 아키텍처로 게시판 개발

  3.1 Model 2 아키텍처 구조

  3.2 Controller 구현하기

  3.2.1 서블릿 생성 및 등록

  3.2.2 Controller 서블릿 구현

  3.3 로그인 기능 구현하기

  3.4 글 목록 검색 기능 구현하기

  3.5 글 상세 보기 기능 구현하기

  3.6 글 등록 기능 구현하기

  3.7 글 수정 기능 구현하기

  3.8 글 삭제 기능 구현하기

  3.9 로그아웃 기능 구현하기


  CLASS 04 MVC 프레임워크 개발

  4.1 MVC 프레임워크 구조

  4.2 MVC 프레임워크 구현

  4.3 MVC 프레임워크 적용

  4.4 EL/JSTL 이용한 JSP 화면 처리


  CLASS 05 Spring MVC 구조

  5.1 Spring MVC 수행 흐름

  5.2 DispatcherServlet 등록 및 스프링 컨테이너 구동

  5.2.1 DispatcherServlet 등록

  5.2.2 스프링 컨테이너 구동

  5.2.3 스프링 설정 파일 등록

  5.3 스프링 설정 파일 변경

  5.4 인코딩 설정


  CLASS 06-07 Spring MVC 적용

  6.1 Spring MVC 적용 준비

  6.2 로그인 기능 구현

  6.3 글 목록 검색 기능 구현

  6.4 글 상세 조회 기능 구현

  6.5 글 등록 기능 구현하기

  6.6 글 수정 기능 구현하기

  6.7 글 삭제 기능 구현하기

  6.8 로그아웃 기능 구현하기

  6.9 ViewResolver 활용하기


  넷째 날(Day 4)

  CLASS 01 어노테이션 기반 MVC 개발

  1.1 어노테이션 관련 설정

  1.2 @Controller 사용하기

  1.3 @RequestMapping 사용하기

  1.4 클라이언트 요청 처리


  CLASS 02 어노테이션으로 게시판 프로그램 구현하기

  2.1 글 등록 기능 구현하기

  2.2 글 목록 검색 구현하기

  2.3 글 상세 보기 구현하기

  2.4 글 수정 기능 구현하기

  2.5 글 삭제 기능 구현하기

  2.6 로그인 기능 구현하기

  2.7 로그아웃 기능 구현하기

  2.8 컨트롤러 통합하기

  2.9 요청 방식에 따른 처리

  2.9.1 method 속성

  2.9.2 JSP에서 Command 객체 사용

  2.9.3 @ModelAttribute 사용

  2.10 Servlet API 사용

  2.11 Controller의 리턴타입

  2.12 기타 어노테이션

  2.12.1 @RequestParam 사용하기

  2.12.2 @ModelAttribute 사용하기

  2.12.3 @SessionAttributes 사용하기


  CLASS 03 프레젠테이션 레이어와 비즈니스 레이어 통합

  3.1 비즈니스 컴포넌트 사용

  3.2 비즈니스 컴포넌트 로딩

  3.2.1 2-Layered 아키텍처

  3.2.2 ContextLoaderListener 등록

  3.2.3 스프링 컨테이너의 관계


  CLASS 04 검색 기능 추가 구현

  4.1 검색 정보 추출

  4.2 Controller 구현

  4.3 DAO 클래스 수정


  CLASS 05 파일 업로드

  5.1 파일 업로드 처리

  5.2 예외 처리

  5.2.1 어노테이션 기반의 예외 처리

  5.2.2 XML 기반의 예외 처리


  CLASS 06 다국어 처리

  6.1 메시지 파일 작성하기

  6.1.1 영어 메시지 파일 작성

  6.1.2 한글 메시지 파일 작성

  6.2 MessageSource 등록

  6.3 LocaleResolver 등록

  6.4 Locale 변경하기

  6.5 JSP 파일 작성


  CLASS 07 데이터 변환

  7.1 JSON으로 변환하기

  7.1.1 Jackson2 라이브러리 내려받기

  7.1.2 HttpMessageConvertor 등록

  7.1.3 링크 추가 및 Controller 수정

  7.1.4 실행 결과 확인

  7.2 XML로 변환하기

  7.2.1 JAXB 2 설정 추가

  7.2.2 Controller 수정

  7.2.3 실행 결과 확인


  다섯째 날(Day 5)

  CLASS 01 Mybatis 프레임워크 시작하기

  1.1 Mybatis 프레임워크 특징

  1.2 Java ORM Plugin 설치

  1.3 프로젝트 생성

  1.4 VO(Value Object) 클래스 작성

  1.5 SQL Mapper XML 파일 작성

  1.6 Mybatis 환경설정 파일

  1.7 SqlSession 객체 생성하기

  1.8 DAO 클래스 작성

  1.9 테스트 클라이언트 작성 및 실행


  CLASS 02 Mapper XML 파일 설정

  2.1 SQL Mapper XML 기본 설정

  2.1.1 Mybatis 구조

  2.1.2 Mapper XML 파일 구조

  2.1.3 〈select〉 엘리먼트

  2.1.4 〈insert〉 엘리먼트

  2.1.5 〈update〉 엘리먼트

  2.1.6 〈delete〉 엘리먼트

  2.2 SQL Mapper XML 추가 설정

  2.2.1 resultMap 속성 사용

  2.2.2 CDATA Section 사용

  2.2.3 SQL 대문자로 설정하기

  2.3 Mybatis JAVA API

  2.3.1 SqlSessionFactoryBuilder 클래스

  2.3.2 SqlSessionFactory 클래스

  2.3.3 유틸리티 클래스 작성

  2.3.4 SqlSession 객체


  CLASS 03 스프링과 MyBatis 연동

  3.1 라이브러리 내려받기

  3.2 Mybatis 설정 파일 복사 및 수정

  3.3 스프링 연동 설정

  3.4 DAO 클래스 구현 - 방법1

  3.5 DAO 클래스 구현 - 방법2

  3.6 MyBatis 연동 테스트

  3.7 Dynamic SQL으로 검색 처리


  CLASS 04 JPA 개념

  4.1 JPA의 특징

  4.2 JPA 프로젝트 생성

  4.3 JPA 라이브러리 내려받기

  4.4 JPA 시작하기

  4.4.1 엔티티 클래스 매핑

  4.4.2 persistence.xml 파일 작성

  4.4.3 클라이언트 프로그램 작성


  CLASS 05 JPA 환경설정

  5.1 영속성 유닛(Persistence Unit) 설정

  5.1.1 영속성 유닛 이름 지정

  5.1.2 엔티티 클래스 등록

  5.1.3 영속성 유닛 프로퍼티 설정

  5.1.4 Dialect 클래스 설정

  5.1.5 JPA 구현체 관련 속성 설정

  5.2 엔티티 클래스 기본 매핑

  5.2.1 @Entity, @Id

  5.2.2 @Table

  5.2.3 @Column

  5.2.4 @GeneratedValue

  5.2.5 @Transient

  5.2.6 @Temporal

  5.3 JPA API

  5.3.1 JPA API 구조

  5.3.2 JPA API 사용


  CLASS 06 스프링과 JPA 연동

  6.1 스프링과 JPA 연동 기초

  6.2 엔티티 매핑 설정

  6.3 스프링과 JPA 연동 설정

  6.4 트랜잭션 설정 수정

  6.5 DAO 클래스 구현

  6.6 BoardServiceImpl 클래스 수정 및 테스트

  
