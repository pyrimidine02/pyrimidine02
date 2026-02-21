# Welcome

## 간략 소개
- 백엔드 개발과 인프라/운영에 관심이 있습니다.
- 위치 기반(LBS) 도메인에서 인증/권한/콘텐츠/지리 데이터 처리와 운영 품질(관측성, 레이트리밋, 오류 표준화)을 다룹니다.
- OpenAPI-first, 계층 분리, RBAC/감사 로그 같은 운영 친화적 원칙을 선호합니다.

## 취미
- 리듬 게임
- 성우/서브컬처 덕질
- 일본 공연 원정
- 기타
- DTM/작곡 (Logic Pro)
- 사진/카메라

## 기술 스택

| 분류 | 목록 |
| --- | --- |
| 언어 | <img src="https://img.shields.io/badge/Kotlin-000000?style=for-the-badge&logo=kotlin&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/C-000000?style=for-the-badge&logo=c&logoColor=FFFFFF"> |
| 백엔드 | <img src="https://img.shields.io/badge/Spring%20Boot-000000?style=for-the-badge&logo=springboot&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Spring%20Security-000000?style=for-the-badge&logo=springsecurity&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-000000?style=for-the-badge&logo=hibernate&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/OpenAPI-000000?style=for-the-badge&logo=openapiinitiative&logoColor=FFFFFF"> |
| 데이터베이스/캐시 | <img src="https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/PostGIS-000000?style=for-the-badge&logo=postgresql&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Redis-000000?style=for-the-badge&logo=redis&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Flyway-000000?style=for-the-badge&logo=flyway&logoColor=FFFFFF"> |
| 인프라/배포 | <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Docker%20Compose-000000?style=for-the-badge&logo=docker&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Nginx-000000?style=for-the-badge&logo=nginx&logoColor=FFFFFF"> |
| 스토리지/클라우드 | <img src="https://img.shields.io/badge/Cloudflare%20R2-000000?style=for-the-badge&logo=cloudflare&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/S3%20Compatible-000000?style=for-the-badge&logo=amazonwebservices&logoColor=FFFFFF"> |
| 관측성/품질 | <img src="https://img.shields.io/badge/Spring%20Actuator-000000?style=for-the-badge&logo=springboot&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Micrometer-000000?style=for-the-badge&logo=prometheus&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/Gradle-000000?style=for-the-badge&logo=gradle&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/ktlint-000000?style=for-the-badge&logo=kotlin&logoColor=FFFFFF"> <img src="https://img.shields.io/badge/detekt-000000?style=for-the-badge&logo=kotlin&logoColor=FFFFFF"> |

## 프로젝트

### Girls Band Tabi
애니메이션·밴드 프로젝트 팬을 위한 위치 기반 순례(LBS) 서비스의 백엔드.
- 인증/권한: 이메일/소셜 로그인, JWT 발급/폐기, 프로젝트 단위 RBAC, 감사 로그
- 콘텐츠/운영: 밴드·유닛·장소·뉴스·라이브 이벤트 관리, 관리자 승인 흐름
- 위치 검증: PostGIS 기반 방문 인증, 지역/계층 필터링, 통계/집계 API
- 인프라 연동: Cloudflare R2(S3 호환) 업로드 파이프라인(서명 URL)
- 운영 품질: Redis 기반 레이트리밋, 구조화 로그, 지표 수집(Actuator/Micrometer), RFC 7807 오류 응답
