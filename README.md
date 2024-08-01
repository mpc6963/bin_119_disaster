# 119_disaster
## 데이터
AI-HUB :https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=71768
위급상황 음성/음향 (고도화) - 119 지능형 신고접수 음성 인식 데이터

## 119_disasterLarge.ipynb
119신고분류(대)
119음성신고데이터 JSON 파일의 대분류 (구급, 구조, 화재, 기타) 분류 예측 코드입니다.
허깅페이스(트랜스포머) 모델 (KcELECTRA-base), torch

## 119_disasterMedium.ipynb
119신고분류(중)
119음성신고데이터 JSON 파일의 중분류 (16종) 분류 예측 코드입니다.
분석중에 config파일을 발견해서 해당 config파일을 수정하고 트레이너 설정 시 config 값으로 설정했습니다. 
