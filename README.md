# SAP ABAP Learning Repository

## 📚 소개
SAP Learning Hub에서 학습한 ABAP 코드 모음입니다.

## 📂 클래스 목록

### 2025년 11월 5일

#### ZCL_20251105_HELLO_WORLD
- Hello World 예제
- 기본 ABAP 구문 연습
- 첫 번째 ABAP 프로그램

#### ZCL_20251105_COMPUTE
- 계산 로직 구현
- 사칙연산 기능
- 변수와 연산자 사용

---

### 2025년 11월 12일

#### ZCL_20251112_BRANCH
- 분기 처리 로직
- IF, CASE 문 활용
- 조건문 연습

---

### 2026년 1월 15일

#### ZCL_20260115_ITERATE
- 반복문 연습
- LOOP, DO, WHILE 구문
- 반복 처리 로직

---

### 2026년 1월 16일

#### ZCL_20260116_DEBUG
- 디버깅 연습
- 중단점(Breakpoint) 사용법
- 변수 값 추적

#### ZCL_20260116_LOCAL_CLASS
- 로컬 클래스 정의
- 클래스 기본 구조
- 메서드 구현

---

### 2026년 1월 19일

#### ZCL_20260119_LOCAL_CLASS_Global_Class
- 전역 클래스와 로컬 클래스 통합
- 클래스 간 상호작용
- 객체지향 프로그래밍 기초

---

### 2026년 1월 21일

#### ZCL_20260121_METHOD_GLOBAL
- 전역 메서드 구현
- 메서드 파라미터 사용
- 반환값 처리

#### ZCL_20260121_METHOD_LOCAL
- 로컬 메서드 구현
- 메서드 호출
- 메서드 간 데이터 전달

---

### 2026년 1월 22일

#### ZCL_20260122_CONSTRUCTOR_GLOBAL
- 전역 클래스의 생성자
- 객체 초기화
- Constructor 메서드 구현

#### ZCL_20260122_CONSTRUCTOR_LOCAL
- 로컬 클래스의 생성자
- 파라미터를 받는 생성자
- 객체 생성 시 초기화 로직

---

### 2026년 1월 23일

#### ZCL_20260123_SELECT_LOCAL (Exercise 12)
- 데이터베이스 테이블에서 데이터 읽기
- SELECT SINGLE 문 사용
- `/dmo/connection` 테이블 조회
- 공항 정보 읽기 (airport_from_id, airport_to_id)
- sy-subrc을 이용한 에러 처리
- INTO 절로 데이터 저장

---

### 2026년 3월 9일

#### ZCL_20260309_CDS_VIEW (Exercise 13)
- CDS View Entity 사용
- `/DMO/I_Connection` CDS View 조회
- Association 활용 (\_Airline-Name)
- Alias 필드명 사용 (DepartureAirport, DestinationAirport)
- 한 번의 SELECT로 여러 테이블 데이터 가져오기
- 항공사 이름 포함 조회 (carrier_name)
- CDS View와 Database Table 비교 학습

---

## 📈 학습 진행 경로
```
Phase 1: 기본 문법 (2025.11)
  └─ Hello World, 계산, 분기문

Phase 2: 반복과 디버깅 (2026.01.15-16)
  └─ 반복문, 디버깅, 로컬 클래스

Phase 3: 객체지향 (2026.01.19-22)
  └─ 클래스, 메서드, 생성자

Phase 4: 데이터베이스 (2026.01.23-03.09)
  └─ SELECT, CDS View, Association
```

## 📅 학습 기간
2025.11.05 ~ 진행중

## 🛠️ 개발 환경
- SAP Learning Hub
- Eclipse ADT (ABAP Development Tools)
- ABAP 7.4+

## 📖 주요 학습 내용
- ABAP 기본 문법
- 객체지향 프로그래밍 (OOP)
- 데이터베이스 조회 (SELECT)
- CDS View & Association
- 디버깅 기법