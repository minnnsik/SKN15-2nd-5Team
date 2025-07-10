# SKN15-2nd-5Team - 유럽 전기 민영화에 따른 고객이탈(churn) 예측 프로젝트

# 1. 팀 소개
오원장
권도원
유의정
조솔찬
홍민식



# 2. 프로젝트 기간


### ✅. 프로젝트 개요
- 데이터 출처: [Kaggle - PowerCo dataset Prediction]   (https://www.kaggle.com/datasets/naiborhujosua/energy-industry)
- 데이터 구성: 총 42개 컬럼, (16,096명 최근 12개월 전력 소비량, 서비스시작일,서비스 종료일, 이탈여부 등)

## 📕 프로젝트명



## ✅ 프로젝트 배경 및 목적
<img width="767" alt="reuter-1 " src="https://github.com/user-attachments/assets/b8f52c02-79b4-45f1-95f9-3f189b663ece" />
<img width="659" alt="reuter-2" src="https://github.com/user-attachments/assets/8f0d5602-74c3-4d91-81a5-aede30a4068c" />
<img width="666" alt="reuter-3" src="https://github.com/user-attachments/assets/5dfdd07f-7b88-4880-9b3d-695427e6f670" />
이 프로젝트의 궁극적 목적은 PowerCo 고객 이탈(Churn) 예측을 통해 회사의 매출 손실을 최소화하고,  효율적인 고객 유지(Retention) 전략을 수립하기 위함입니다.



## 🖐️ 프로젝트 소개

## ❤️ 기대효과

## 👤 대상 사용자



# 4. 기술 스택

### AI & 데이터 처리

[](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)![](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)![](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)![](https://img.shields.io/badge/scikitlearn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

### 실험 및 개발 환경
![](<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">)


### 머신러닝 모델



###버전관리 및 협업


## 데이터 셋 설명 


## 탐색적 데이터 분석(EDA)
###1. 데이터 전처리 
 #   Column                    Non-Null Count  Dtype  
---  ------                            --------------  -----  
 0   id (고객ID)                                        16096 non-null  object 
 1   channel_sales (판매채널)                            16096 non-null  object 
 2   cons_12m (최근 12개월 전력 소비량)                     16096 non-null  int64  
 3   cons_gas_12m (최근 12개월 가스 소비량)                 16096 non-null  int64  
 4   cons_last_month 직전 월 (지난달) 소비량                16096 non-null  int64  
 5   date_activ (서비스 시작일)                           16096 non-null  int64  
 6   date_end (계약 종료일)                               16096 non-null  int64  
 7   date_modif_prod (상품 요금제 변경일)                   16096 non-null  int64  
 8   date_renewal (계약 갱신일)                           16096 non-null  int64  
 9   forecast_cons_12m (향후 12개월 소비 예측)              16096 non-null  float64
 10  forecast_cons_year (향후 연간 소비 예측)               16096 non-null  int64  
 11  forecast_discount_energy (에너지 할인 금액 예측)        16096 non-null  float64
 12  forecast_meter_rent_12m (향후 12개월 계량기 임대료 예측)  16096 non-null  float64
 13  forecast_price_energy_p1 (P1구간 에너지 단가 예측)      16096 non-null  float64
 14  forecast_price_energy_p2 (P2 구간 에너지 단가 예측)     16096 non-null  float64
 15  forecast_price_pow_p1 (P1 구간 전력 (수요) 단가 예측)    16096 non-null  float64
 16  has_gas  (가스 사용 여부)                             16096 non-null  object 
 17  imp_cons (수입 전력 소비량)                           16096 non-null  float64
 18  margin_gross_pow_ele (전력,전기 총마진)               16096 non-null  float64
 19  margin_net_pow_ele (전력,전기 순마진)                 16096 non-null  float64
 20  nb_prod_act (활성 제품 (요금제) 수)                   16096 non-null  int64  
 21  net_margin (순마진)                                16096 non-null  float64
 22  num_years_antig (가입기간 (년))                     16096 non-null  int64  
 23  origin_up (가입 경로)                              16096 non-null  object 
 24  pow_max (최대 전력 수요)                            16096 non-null  float64
 25  churn (이탈여부 (0=유지, 1=이탈))                    16096 non-null  int64  
dtypes: float64(11), int64(11), object(4)
memory usage: 3.2+ MB








# 5. 수행결과(분석 및 예측 결과)



# 6. 한 줄 회고

