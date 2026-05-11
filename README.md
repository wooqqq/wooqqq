<div align="center">

# 안녕하세요, 우혜지입니다 👋

**Java / Spring Boot 백엔드 개발자**

SSAFY 11기 수료

[![GitHub](https://img.shields.io/badge/GitHub-wooqqq-181717?style=flat-square&logo=github)](https://github.com/wooqqq)

</div>

---

## 🛠 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-FF7800?style=flat-square&logo=hibernate&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-673DE6?style=flat-square)
![SSE](https://img.shields.io/badge/SSE-0089CF?style=flat-square)

**Database & Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Frontend & Data**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 🚀 Projects

### 📌 개인 프로젝트

**[그룹웨어 트래픽 과부하 개선](https://github.com/wooqqq/groupware-performance-test)**

`2026.04` · 개인

실무에서 인사발령 공문 게시 시 전 직원이 동시 접속하며 서버가 다운되는 문제를 직접 재현하고 개선한 프로젝트.
Redis 캐싱 도입 후 nGrinder + Grafana로 수치 검증.

| 지표 | 개선 전 | 개선 후 | 개선율 |
|---|---|---|---|
| P95 응답시간 | 356ms | 102ms | **-71%** |
| Mean Test Time | 221ms | 79ms | **-64%** |
| DB 커넥션 활성 | 12.4개 | 1.52개 | **-88%** |
| DB 커넥션 대기 | 44~80개 | 2.52개 | **-97%** |

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![nGrinder](https://img.shields.io/badge/nGrinder-00A98F?style=flat-square)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

<br>

**[선착순 쿠폰 발급 시스템](https://github.com/wooqqq/coupon-system)**

`2026.05` · 개인

동시 요청 환경에서 Race Condition이 발생하는 과정을 직접 재현하고, 단계별(synchronized → DB 락 → Redisson 분산락)로 해결하며 각 락 전략의 트레이드오프를 학습한 프로젝트.

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Redisson](https://img.shields.io/badge/Redisson-DC382D?style=flat-square)

---

### 📌 팀 프로젝트

**[WONTOUCH](https://github.com/wooqqq/wontouch)** — 경제 교육 게임 서비스

`2024.08 ~ 2024.10` · SSAFY 11기 특화 프로젝트 · **팀장 / BE**

게임을 통해 뉴스와 경제 흐름을 학습하는 멀티플레이 게임 서비스. MSA 구조로 Auth / API / Mileage 서버를 분리 설계.

- 카카오·구글 OAuth2 소셜 로그인 + JWT + Redis Refresh Token — Auth 서버 전체 구축
- 마일리지·티어포인트 마이크로서비스 (MongoDB) — 게임 결과 연동, 주간 랭킹 초기화
- SSE 기반 실시간 알림 (친구 신청·게임 초대), MongoDB 저장 및 자동 만료 처리
- Redis로 온라인 친구 실시간 조회, 친구 신청·수락·거절·삭제 전 기능

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-0089CF?style=flat-square)

<br>

**[ODD (우리동네단골)](https://github.com/oodongdan/ODD)** — 재구매 상품 추천 서비스

`2024.10 ~ 2024.11` · SSAFY 11기 자율 프로젝트 (GS리테일 기업연계) · **BE / 추천 알고리즘**

편의점·슈퍼 배달·픽업 고객 대상 개인화 재구매 추천 앱 및 관리자 대시보드. Python(FastAPI)과 Java 양쪽에서 알고리즘을 구현하고 서버 간 연동.

- 시간대별 재구매 추천 알고리즘 — 사용자 구매 빈도 분석, TaskScheduler로 자동 알림 발송
- 주기별 재구매 추천 알고리즘 — 재구매 주기 학습 후 경과 시점에 FCM 푸시 알림
- FCM(Firebase Cloud Messaging) 알림 시스템 — Redis에 토큰 저장, MongoDB에 이력 관리
- 대시보드 API — 재구매 사용자 수·비율, 성별·연령대별 분석 데이터 제공

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)

<br>

**[UKIDS](https://github.com/wooqqq/UKIDS)** — 가족 유대감 플랫폼

`2024.07 ~ 2024.08` · SSAFY 11기 공통 프로젝트 · **팀장 / BE**

가족 채팅·영상통화·그림일기·퀴즈·타임캡슐로 가족 간 유대감을 쌓는 플랫폼.

- WebSocket + STOMP + Redis Pub/Sub 기반 실시간 채팅 — 확장성을 고려한 분산 메시지 처리 구조
- STOMP 연결 시 JWT 인증 인터셉터(`StompHandler`) 구현
- 가족방 도메인 — SHA-256 고유 초대코드 생성, BCrypt 비밀번호 암호화, 역할 기반 접근제어
- Spring Security + JWT 인증 체계 전체 설계

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket+STOMP-673DE6?style=flat-square)
![Redis](https://img.shields.io/badge/Redis_Pub/Sub-DC382D?style=flat-square&logo=redis&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

---

### 📌 그 외

| 프로젝트 | 기간 | 설명 |
|---|---|---|
| [WeFlea](https://github.com/likelion3-team3/WeFlea) | 2023.07 | 멋쟁이사자처럼 — 여러 중고거래 사이트를 한 곳에서 검색·비교 (Selenium 크롤링, WebSocket 채팅) |
| [My Own Tin](https://github.com/SSAFY-11th-MyRoutine/my-own-tin) | 2024.05 ~ 06 | SSAFY 관통 프로젝트 — 나만의 운동 루틴 관리 앱 (Vue.js) |

---

## 📚 Algorithm

[![solved.ac](https://mazassumnida.wtf/api/v2/generate_badge?boj=sge0225)](https://solved.ac/sge0225)

- 📂 [백준 (BaekjoonHub 자동 업로드)](https://github.com/wooqqq/algorithm_BOJ)
- 📂 [알고리즘 풀이 모음](https://github.com/wooqqq/algorithm)

<!-- ---

## 🏫 우아한테크코스 프리코스

우아한테크코스 프리코스에 참여하며 객체지향 설계와 TDD를 학습했습니다.

| 미션 | 저장소 |
|---|---|
| 숫자 야구 | [java-baseball](https://github.com/wooqqq/java-baseball) |
| 자동차 경주 | [java-racingcar-7](https://github.com/wooqqq/java-racingcar-7) |
| 로또 | [java-lotto-7](https://github.com/wooqqq/java-lotto-7) |
| 문자열 덧셈 계산기 | [java-calculator-7](https://github.com/wooqqq/java-calculator-7) |
| 온콜 | [java-oncall-6](https://github.com/wooqqq/java-oncall-6-wooqqq) |

--- -->
<!--
<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=wooqqq&show_icons=true&theme=default&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wooqqq&layout=compact&hide_border=true)

</div>
-->
