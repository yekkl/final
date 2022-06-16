# final
## 선형 회귀 분석
선형 회귀 분석은 독립변수, 상수항, 종속변수 사이의 관계를 모델화 하는 것으로 두 변수 사이의 관계일 경우 단순 회귀분석이라고 하며 여러개의 변수를 다루는 다중 회귀분석이 있습니다.
### 제곱 오류 합계 계산하기
각 데이터 포인트에 대해 실제값과 예측값의 차이를 찾는다. 이 차이를 "오류(error)"라고 한다. 그런 다음에 오류를 제곱한다. 제곱한느 이유는 서로 값의 차이를 높이면서 동시에 절대값을 만들어줌으로써 서로 제곱 오류 합계를 비교하기 쉽기 때문이다. 이 프로세스를 모든 데이터마다 반복한다. 그 다음으로 모든 데이터 포인트에 대해 계산된 모든 제로 오류를 합산한다. 그러면 제곱 오류 합계가 된다.
+ y = mx+b
선형 회귀는 직선의 방정식인 y=mx+b를 사용한다. x는 독립변수, m은 기울기, b는 y절편이다. 제곱 오류 합계가 최솟값인 방정식의 해를 찾기 위해 '최소제곱법' 방법을 사용한다.
### 최소
#### 예시 (공부시간에 따른 성적)
|시간|성적|
|---|---|
|3|35|
|4|50|
|5|45|
|6|64|
|7|66|
|8|70|
|...|...|

데이터 6개의 성적 평균 값은 55(35+50+45+64+66+70/6)이다. 따라서 y=55방정식을 직선으로 표현할 수 있다. 이 직선은 선형 회귀에 얼마나 잘 부합하는지 확인할 때 레퍼런스로 활용된다. 이 직선과의 거리를 비교하기 위해 '제곱 오류 합계'매트릭을 사용한다.

![image](https://user-images.githubusercontent.com/101376842/174037154-169bee09-e6f0-45c5-9b0e-6b5dfcce1883.png)

