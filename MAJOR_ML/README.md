[2-2 머신러닝 전공 수업에서 진행한 팀별 competition]

주제: Survey 응답 예측 Competition (Accuracy)

느낀점:
1. feature 생성 시 응답률과 같은 target data를 파생해서 만드는 것도 중요하지만 과할 경우 오히려 과적합을 일으킬 수 있음
2. feature 생성 시 수치형 변수 개별 변형을 통해 ex) 제곱, 세제곱 등을 활용하여 유의미한 통계량 값을 만드는 것에 focus
3. feature 생성 시 수치형 변수에만 집중하는 것이 아니라 범주형 변수에도 어떤 식으로 활용할 수 있는지 잘 생각 (이번 competiton에서 가장 중요하게 작용 ex) 범주를 문자열화 하여 단순 join
4. 해당 모형을 기반으로 상대적 Feature 기여도를 계산했다고 해서 무조건 최적의 set이 아닐 수도 있음

보완해야될 점: <br/>
 다양한 모델에 적용하기 위한 이질적인 Feature set을 많이 만들어서 실험하고 계산해야되는데 모델을 돌리는데 있어서 시간적 한계가 존재하여 이질적인 Feature set 생성이 부족했고 DNN모델 아키텍쳐 구현에 대한 이해도가 낮아 제대로 구현해보지 못함


![KakaoTalk_20240312_234150187](https://github.com/sangwook01/Competition/assets/133327420/02207539-3817-4e51-bb01-dcef8ecb7b9e)
![KakaoTalk_20240312_234150187_01](https://github.com/sangwook01/Competition/assets/133327420/f6c67626-bcd2-43be-97e9-2e801dad6718)
