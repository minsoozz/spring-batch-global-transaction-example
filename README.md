# spring-batch-global-transaction-example

## 구현 기능
- Spring Quartz + Spring Batch 를 활용하여 정해진 시간에 배치 작업 수행
-  `데이터베이스 1` 의 값을 `데이터베이스 2`로 마이그레이션
- `데이터베이스 1` 과 `데이터베이스 2` 는 하나의 트랜잭션 안에서 처리하도록 구현
- 마이그레이션 도중 예외 발생 시 롤백

## 개발 환경
- Java 17
- Spring Boot 2.7
- Spring Batch
- JPA
- QueryDSL
