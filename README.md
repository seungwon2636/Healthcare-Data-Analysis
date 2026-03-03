# Healthcare-Data-Analysis
# 🏥 헬스케어 데이터 시각화 분석 (Healthcare Data Analysis)

Power BI를 활용하여 구축된 **의료 데이터 시각화 대시보드**입니다. 다양한 환자 정보, 다빈도 질환, 각 병원별 통계 등 방대한 의료 데이터를 직관적으로 파악하고 분석할 수 있도록 구성되었습니다.

## 📊 대시보드 주요 구성 (Pages)

이 대시보드는 크게 두 가지 핵심 페이지로 나뉘어 있습니다.

### 1️⃣ 질환별 정보 (Disease Information)
특정 주요 질환(Medical Condition)을 중심으로 환자들의 분포와 통계를 다각도로 분석합니다.
* **환자 인구통계 분석**: 성별(Gender), 연령대(Age Group), 혈액형(Blood Type)에 따른 주요 질환 비율
* **임상 및 처방 정보**: 주요 복용 약물(Medication)과 검사 결과 비율 (Normal, Inconclusive, Abnormal Ratio)
* **질환별 비용 및 기간**: 질환별 평균 입원 기간(Length of Stay) 및 총 청구 금액(Billing Amount) 비교

### 2️⃣ 병원별 정보 (Hospital Information)
환자가 방문한 병원(Hospital)을 기준으로 의료 서비스 제공 현황을 분석합니다.
* **위치 기반 모니터링**: 지도(Map/EsriVisual)를 활용한 병원별 환자 분포 시각화
* **연도별 추이 분석**: 연도별 입원 환자 수 추세 (Year of Admission)
* **재무 및 보험 데이터**: 병원별 청구 범위 및 주요 보험사(Insurance Provider)별 환자 비중

## 🔍 활용된 주요 데이터 필드
해당 리포트는 다음과 같은 핵심 데이터 필드들을 가공하여 인사이트를 도출했습니다.
* **환자 기본 정보**: `Age`(연령), `Gender`(성별), `Blood Type`(혈액형)
* **임상 데이터**: `Medical Condition`(의료 조건/질환), `Disease Description`(질환 상세), `Medication`(처방 약물)
* **입원/재무 데이터**: `Hospital`(입원 병원), `Year of Admission`(입원 연도), `Length of Stay`(입원 기간), `Billing Amount`(청구액), `Insurance Provider`(보험사)

## 🛠️ 기술 스택 및 도구
* **Microsoft Power BI**: 데이터 전처리, 모델링 및 인터랙티브 대시보드 시각화

## ⚙️ 실행 및 사용 방법
이 프로젝트는 `.pbix` 파일 형태로 제공됩니다.

1. 본 저장소(Repository)의 [Healthcare Data Analysis.pbix](Healthcare%20Data%20Analysis.pbix) 파일을 다운로드합니다.
2. PC에 **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)**이 설치되어 있어야 합니다.
3. 다운로드한 `.pbix` 파일을 실행하면 전체 리포트 뷰와 사용된 데이터 모델링 구조를 확인하실 수 있습니다.
4. 페이지 내 슬라이서(필터)를 클릭하며 데이터를 인터랙티브하게 탐색해 보세요.
