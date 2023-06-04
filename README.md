# Querydsl 학습

### 엔티티 클래스
<img src = "https://user-images.githubusercontent.com/105557972/243177391-84def019-6328-4131-ae5c-956977acba55.png"></img>
### ERD
<img src = "https://user-images.githubusercontent.com/105557972/243177392-be446e15-adc7-4025-b8b0-ca31105d314c.png"></img>

### 기본 문법
+ JPQL vs Querydsl
+ 기본 Q-Type 활용
+ 검색 조건 쿼리
+ 결과 조회
+ 정렬
+ 페이징
+ 집합
+ 조인 - 기본 조인
+ 조인 - on절
+ 조인 - 페치 조인
+ 서브 쿼리
+ Case 문
+ 상수, 문자 더하기
### 중급 문법
+ 프로젝션과 결과 반환
  + 기본
  + DTO 조회
  + @QueryProjection
+ 동적 쿼리 - BooleanBuilder 사용
+ 동적 쿼리 - Where 다중 파라미터 사용
+ 수정, 삭제 벌크 연산
+ SQL function 호출하기
### 실무 활용 - 순수 JPA와 Querydsl
+ 동적 쿼리와 성능 최적화 조회 - Builder 사용
+ 동적 쿼리와 성능 최적화 조회 - Where절 파라미터 사용
+ 조회 API 컨트롤러 개발
### 실무 활용 - 스프링 데이터 JPA와 Querydsl
+ 스프링 데이터 JPA 리포지토리로 변경
+ 사용자 정의 리포지토리
+ 스프링 데이터 페이징 활용
  + Querydsl 페이징 연동
  + CountQuery 최적화
  + 컨트롤러 개발
### 스프링 데이터 JPA가 제공하는 Querydsl 기능
+ 인터페이스 지원 - QuerydslPredicateExecutor
+ Querydsl Web 지원
+ 리포지토리 지원 - QuerydslRepositorySupport
+ Querydsl 지원 클래스 직접 만들기
