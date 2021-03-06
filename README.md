<div align="center">
  <h1> 🏠 ML 분류모델을 이용한 airbnb 추천시스템 </h1>
  <br>
  </div>
  
  ## 프로젝트 개요 
  - 📅 프로젝트 기간 : 2021.08.31 - 2021.09.03   
  - 프로젝트 목표 : airbnb를 처음 사용하는 사람들을 위한 추천기능 구현
  <br>
  
  ## 프로젝트 과정 
  - 데이터 : kaggle의 미국 airbnb 오픈 데이터 [🔗링크](https://www.kaggle.com/kritikseth/us-airbnb-open-data)
  - 데이터 전처리 
    - 시각화를 통해 데이터의 패턴 발견 
    - 데이터의 특이성 확인
    - 결측치 제거
    - 이상치 제거 
    - 데이터 전처리 결과 : 226,030개의 행 -> 66,354개의 행 
  - Feature Engineering 
    - popularity : 월 평균 리뷰 수를 기준으로 5단계로 분류한 특성 
    - recommend : popularity를 기준으로 이진 분류한 특성   
  - 모델 학습 
     
     <img width="800" alt="스크린샷 2022-02-10 오후 10 15 35" src="https://user-images.githubusercontent.com/86868063/153415804-b9dd9def-3270-4e28-ac7f-25f834695407.png">

  <br>
  
  ## 프로젝트 결과 
  - 월 평균 리뷰 수를 기준으로 추천기능 모델 구현
  - 최종모델의 Accuracy: 0.85, Precison: 0.68, Recall: 0.51  
  <br>
  
  ## 프로젝트 회고
  - Machine Learning만을 이용해 추천 모델을 구현하고자 노력했으나, 추천 알고리즘에 대한 이해가 부족한 상태로 진행한 프로젝트로 아쉬움이 남는다. 
  - 데이터의 다양한 특성들 중에 월 평균 리뷰 수를 추천의 기준으로 사용했는데, 다양한 특성을 사용해 추천의 기준으로 사용했다면 더 좋았을 것 같다. 

  
