<div align="center">

# Hi, I'm Yerin 👋

### Backend Developer

Java & Spring Boot를 기반으로  
**안정성과 확장성을 고려한 백엔드 시스템**을 개발합니다.

실패와 재시도, 데이터 정합성, 비동기 처리 구조를 고민하고  
AI 기능을 실제 서비스 흐름에 안정적으로 연결하는 데 관심이 있습니다.

<br/>

<a href="mailto:kyr0686@naver.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/nenini">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</a>

</div>

---

## 👩🏻‍💻 About Me

- Java / Spring Boot 기반 백엔드 개발을 중심으로 공부하고 있습니다.
- 정상 동작뿐 아니라 **실패, 재시도, 중복 요청, 데이터 정합성**까지 고려하는 개발에 관심이 있습니다.
- Redis 기반 비동기 처리, AI API 연동, Docker 기반 배포를 경험했습니다.
- 구현 이후 테스트와 성능 측정을 통해 구조를 개선하는 과정을 중요하게 생각합니다.

---

## 🛠 Tech Stack

### Languages
<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA%2FHibernate-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
</p>

### Database & Infra
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
</p>

### Tools
<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</p>

---

## 🚀 Featured Projects

### 01. JobQ
> **Fault-Tolerant Distributed Job Queue**

`Java` `Spring Boot` `Redis Streams` `PostgreSQL` `Prometheus` `k6`

외부 API 실패와 지연 상황에서도 작업을 안정적으로 처리하기 위해  
직접 설계한 비동기 Job 처리 시스템입니다.

- Retry, DLQ, Idempotency, Lease 기반 신뢰성 구조 설계
- Testcontainers 기반 Job 생성 → 처리 → DLQ → Replay 흐름 검증
- 약 **40,000건 부하 테스트**
- DB I/O 개선 후 평균 응답 시간 **9.15ms → 8.35ms**

🔗 [Repository](https://github.com/nenini/JobQ)

<br/>

### 02. Trendlog
> **Personalized Trend Analysis & Recommendation**

`Spring Boot` `PostgreSQL` `Redis` `FastAPI` `Docker` `AWS EC2`

사용자 활동과 외부 데이터를 활용해  
트렌드 분석과 개인화 추천을 제공하는 서비스입니다.

- Spring Boot와 FastAPI 기반 추천 서비스 연동
- LightFM 개인화 추천 및 SentenceTransformer 유사 트렌드 분석
- 추천 컨테이너 메모리 사용량 약 **500MiB 수준으로 안정화**
- 컨테이너 **재시작 0건**, 추천 정확도 **93.6% 유지**

🔗 [Repository](https://github.com/sssu22/BACK)

<br/>

### 03. DotDot
> **AI Meeting Assistant**

`Spring Boot` `MySQL` `React` `OpenAI API` `Google Search API`

회의 기록 이후 요약부터 후속 업무 정리까지 연결하는  
AI 회의 관리 서비스입니다.

- STT → 요약 → 자료 추천 → 태스크 추출 후처리 파이프라인 설계
- Chunking + Map-Reduce 방식으로 장시간 회의 처리 구조 개선
- OpenAI 기반 검색 질의 생성 및 검색 결과 재정렬
- **2025 IT 프로젝트 프로리그 우수상**

🔗 [Repository](https://github.com/DotDot5/DotDot_BE)

---

## 🎓 Experience

**Samsung Software & AI Academy, SSAFY 15th**  
Java · Web · Algorithm · AI

**B.S. in Computer Science, Soongsil University**

---

## 🧩 Algorithm

<div align="center">

<a href="https://solved.ac/kyr0686">
  <img
    src="http://mazassumnida.wtf/api/v2/generate_badge?boj=kyr0686"
    height="150"
    alt="Solved.ac Profile"/>
</a>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nenini&theme=github_dark"
  width="650"
/>

<br/>

<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=nenini&theme=github_dark"
  width="320"
/>
<img
  src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=nenini&theme=github_dark"
  width="320"
/>

</div>
<div align="center">

### 📫 Contact

**kyr0686@naver.com**

</div>
