> **📌 참고**
> 이 워크샵은 **Microsoft Foundry 새로운 포털(2026년 기준)** 기반으로 작성되었습니다.
> 
> 기존 Classic 포털 기반 워크샵은 [AzureAIFoundryWorkshop](https://github.com/wonsungso/AzureAIFoundryWorkshop)을 참조하세요.

# 🚀 Microsoft Foundry Workshop - Portal

이 워크샵은 [Microsoft Foundry 포털](https://ai.azure.com/)에서 생성형 AI 애플리케이션을 설계하고 실험하고 평가하는 전체 흐름을 직접 따라가도록 구성되어 있습니다.

실습의 중심은 다음 항목입니다.

- **검색**과 **모델 카탈로그**에서 모델을 탐색하고 배포하기
- **빌드**에서 플레이그라운드와 에이전트를 구성하기
- **작업**과 **관리자**에서 프로젝트 연결과 운영 리소스를 설정하기

---

### 1. Microsoft Foundry 기본 구성
- [Microsoft Foundry 포털](https://ai.azure.com/)에서 프로젝트 생성
- Azure AI Search, Azure Storage 등 외부 리소스 준비
- **작업 > 관리자**에서 프로젝트 연결 구성
- 실습용 리소스 그룹과 프로젝트 정보 확인

### 2. 플레이그라운드 체험
- **검색 > 모델** 또는 **모델 카탈로그**에서 모델 배포
- **채팅 플레이그라운드**에서 시스템 프롬프트 실험
- **데이터 원본 추가**를 통해 파일 업로드 기반 RAG 구성
- 금융 상품 문서를 기반으로 검색 품질 점검

### 3. 첫 번째 에이전트 구현 – 사용자 프로필 추출
- **빌드 > 에이전트**에서 `CreditProfileAgent` 생성
- `user_card_credit_summary_sample.json`을 지식으로 추가
- 사용자 조건에 맞는 프로필 JSON 추출 프롬프트 설계
- 플레이그라운드에서 응답 형식 검증

### 4. 멀티 에이전트 구현 – 펀드 추천
- `FundRecommendationAgent` 생성
- `CreditProfileAgent`를 Connected agent로 연결
- `fund_products_for_embedding_part_001.json` 기반 추천 로직 구성
- 추천 결과를 요약, 후보 상품, 근거 형태로 출력

---

## ⏱️ 권장 시간 배분 (총 2시간 30분)

- Foundry 구성 & 플레이그라운드 체험: **50분**
- 첫 번째 에이전트 구현: **40분**
- 휴식: **10분**
- 멀티 에이전트 구현: **50분**

---

## ✅ 사전 준비

- Azure 구독
- 리소스 생성이 가능한 권한
- Microsoft Foundry 사용 권한
- [Azure 포털](https://portal.azure.com) 기본 사용 경험
- 지원 리전에서 모델 배포가 가능한 Quota

---

이 과정을 통해 참가자는 **모델 배포 → 데이터 연결 → 에이전트 구성**으로 이어지는 Microsoft Foundry의 최신 개발 흐름을 한 번에 경험할 수 있습니다.

---

## Contributors

| Name | GitHub |
|---|---|
| Wonsung So | [@wonsungso](https://github.com/wonsungso) |
