# ⚡ 전기차 충전소 사용자/충전기 유형 예측 시스템

전기차 충전소 데이터를 활용하여 사용자 유형과 충전기 유형을 예측하는 모델을 개발한 프로젝트입니다.  
VotingClassifier 기반으로 다양한 머신러닝 모델을 앙상블하여 예측 성능을 개선하였으며, 데이터 불균형 문제를 개선하기 위해 SMOTEENN 기법을 적용하였습니다.

---

## 🔗 링크

- 📄 [고급 AI 프로젝트 보고서 (PDF or DOCX)](https://drive.google.com/...) *(업로드 시 링크 교체)*

- 📁 [GitHub Repository (Code only, with README)](https://github.com/...) *(코드 업로드 시 링크 교체)*

📦 Data Files

- 🔗 [Kaggle EV Charging Dataset](https://www.kaggle.com/datasets)

- 🔗 [OpenChargeMap Dataset](https://openchargemap.org)

---

## 🚀 실행 방법 (How to Run)

본 프로젝트는 Jupyter Notebook 또는 Google Colab 환경에서 실행 가능합니다.

### 1️⃣ 데이터 준비

- Kaggle EV 충전 데이터 다운로드  
- OpenChargeMap 데이터 다운로드 및 병합  
- 전처리 및 파생 변수 생성

### 2️⃣ Colab / Jupyter 노트북 열기

- GitHub 레포지토리 또는 개인 Colab 환경에서 실행

### 3️⃣ 실행 순서

1. 데이터 로딩
2. 전처리 및 인코딩
3. 데이터 불균형 처리 (SMOTEENN)
4. VotingClassifier 모델 학습 및 평가

---

## 📚 기술 스택

- Python
- Scikit-learn
- LightGBM
- XGBoost
- CatBoost
- RandomForest
- Logistic Regression
- SMOTEENN
- Pandas
- Matplotlib
- Seaborn

---

## 📝 참고

- 본 프로젝트는 AI융합학과 고급 AI 교과목의 기말 프로젝트로 진행되었습니다.
- 데이터 출처:  
  - Kaggle: EV Charging Dataset  
  - OpenChargeMap: Global Public Charging Stations
