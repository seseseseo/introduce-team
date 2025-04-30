# 🧑‍💻 팀 자기소개 관리 API 프로젝트

팀원들이 자기소개 정보를 등록하고, 수정하고, 조회할 수 있는 Spring Boot 기반 RESTful API 프로젝트입니다.  
JWT 기반 인증을 통해 본인의 소개글만 수정/삭제할 수 있으며, 팀 개발 및 Git 협업을 실습하기 위한 목적으로 만들어졌습니다.

---

## 📌 주요 기능

### 🔐 회원 인증
- 회원가입 (username, password)
- 로그인 (JWT 토큰 발급)
- JWT 인증을 통한 API 접근 제어

### 📝 자기소개 기능
- 자기소개 등록
- 전체 소개글 조회
- 특정 소개글 조회
- 본인의 소개글 수정 / 삭제

---

## 🛠 사용 기술 스택

| 구분 | 내용 |
|------|------|
| Language | Java 17 |
| Framework | Spring Boot 3.x |
| ORM | Spring Data JPA |
| Auth | Spring Security + JWT |
| DB | H2 (개발용), MySQL (선택) |
| 문서화 | SpringDoc OpenAPI (Swagger UI) |
| 협업 | GitHub, Git Flow 전략 사용 |

---

## 📁 프로젝트 구조 (도메인 기반 분리)


## ERD
![image](https://github.com/user-attachments/assets/c9ffd149-f0b0-4963-983c-3b2a6619c3a8)
