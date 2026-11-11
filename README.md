# 머신러닝과 딥러닝 기초 — 실습 노트북

『머신러닝과 딥러닝 기초 — 학습의 원리에서 심층 신경망까지』(신영학 지음)의 장별 실습 노트북입니다.

아래 표의 **Colab에서 열기**를 누르면 설치 없이 브라우저에서 바로 실행할 수 있습니다. 코드를 바꿔 보려면 Colab 메뉴 [파일] → [Drive에 사본 저장]으로 내 드라이브에 복사한 뒤 실행하세요. 모든 노트북은 GPU 없이 기본 런타임(CPU)으로 실행됩니다. Colab 사용법은 책의 부록 A에 있습니다.

| 장 | 노트북 | Colab |
|---|---|---|
| 1장 인공지능, 머신러닝, 딥러닝 | [`ch01_rules_vs_learning.ipynb`](notebooks/ch01_rules_vs_learning.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch01_rules_vs_learning.ipynb) |
| 2장 머신러닝은 어떻게 배우나 | [`ch02_how_ml_learns.ipynb`](notebooks/ch02_how_ml_learns.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch02_how_ml_learns.ipynb) |
| 3장 데이터 살펴보고 준비하기 | [`ch03_prepare_data.ipynb`](notebooks/ch03_prepare_data.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch03_prepare_data.ipynb) |
| 4장 모델 평가와 하이퍼파라미터 고르기 | [`ch04_model_evaluation.ipynb`](notebooks/ch04_model_evaluation.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch04_model_evaluation.ipynb) |
| 5장 결정 트리와 앙상블 | [`ch05_trees_ensembles.ipynb`](notebooks/ch05_trees_ensembles.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch05_trees_ensembles.ipynb) |
| 6장 비지도 학습: 군집과 차원 축소 | [`ch06_unsupervised.ipynb`](notebooks/ch06_unsupervised.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch06_unsupervised.ipynb) |
| 7장 선형 회귀 | [`ch07_linear_regression.ipynb`](notebooks/ch07_linear_regression.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch07_linear_regression.ipynb) |
| 8장 경사 하강법 | [`ch08_gradient_descent.ipynb`](notebooks/ch08_gradient_descent.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch08_gradient_descent.ipynb) |
| 9장 로지스틱 회귀와 소프트맥스 회귀 | [`ch09_logistic_softmax.ipynb`](notebooks/ch09_logistic_softmax.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch09_logistic_softmax.ipynb) |
| 10장 직선을 넘어서: 다층 신경망 | [`ch10_mlp.ipynb`](notebooks/ch10_mlp.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch10_mlp.ipynb) |
| 11장 오차 역전파 | [`ch11_backprop.ipynb`](notebooks/ch11_backprop.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch11_backprop.ipynb) |
| 12장 케라스로 만드는 심층 신경망 | [`ch12_keras.ipynb`](notebooks/ch12_keras.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch12_keras.ipynb) |
| 13장 일반화와 모델 고르기 | [`ch13_generalization.ipynb`](notebooks/ch13_generalization.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/ch13_generalization.ipynb) |
| 부록 B 파이썬과 넘파이 빠른 복습 | [`appB_python_numpy.ipynb`](notebooks/appB_python_numpy.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/ml-dl-basics/blob/main/notebooks/appB_python_numpy.ipynb) |

노트북 끝의 **실습 문제**는 직접 코드를 써서 풀어 보는 문제입니다.

## 실행 환경

2026년 11월 Google Colab(Python 3.13, NumPy 2.4, pandas 2.2, scikit-learn 1.6, TensorFlow 2.21, Keras 3.13)에서 실행을 확인했습니다. 라이브러리 버전이 바뀌면 결과 숫자가 책과 조금 다를 수 있습니다. 자세한 내용은 책의 부록 A를 참고하세요.

## 데이터 출처

실습 데이터는 각 노트북에서 불러옵니다. Palmer Penguins(seaborn 예제 데이터, CC0), 위스콘신 유방암 진단·캘리포니아 주택·손글씨 숫자(scikit-learn 내장 데이터)와 노트북에서 직접 만든 합성 데이터를 씁니다. 이용 조건은 각 배포처를 따릅니다.
