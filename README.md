# [파이선으로 베이지안 모델링하기](https://github.com/markdregan/Bayesian-Modelling-in-Python)

![파이선으로 베이지안 모델링하기](/graphics/cover.png)

이 문서는 "파이선으로 베이자인 모델링하기"입니다. 파이선으로 베이지안 기법을 적용하길 원하는 사람들을 위한 입문서이지요.
파이선[PYMC3](https://github.com/pymc-devs/pymc3) 를 사용합니다.
해당 입문서는 베이지안 기법에 대한 입문서가 아닙니다.
프로그래밍 Cookbook 에 더 가깝다고 할 수 있겠네요.
베이지안 기법에 이미 친숙하고, 파이선을 통해 구현해보고 싶어하는 사람들에게 유용할 거에요.
해당 입문서의 목차는 다음과 같습니다.

### 목차
- [**Introduction**](http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%200.%20Introduction.ipynb)
    - 베이지안 통계학을 배우면 좋은 점
    - Hangout chat data 를 읽고 파싱해보자
    
- [**Section 1: Estimating model parameters**](http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%201.%20Estimating%20model%20parameters.ipynb)
    - 푸아송 모델 파라메터를 예측하는 빈도주의 기법 (Optimization routine)
    - 푸아송 모델 파라메터를 예측하는 베이지안 기법 (MCMC)

- [**Section 2: Model checking & comparison**](http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%202.%20Model%20checking.ipynb)
    - Posterior predictive check
    - Bayes factor
    
- [**Section 3: Hierarchal modeling**](http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%203.%20Hierarchical%20modelling.ipynb)
    - Model pooling (separate models)
    - Partial pooling (hierarchal models)
    - Shrinkage effect of partial pooling
    
- [**Section 4: Bayesian regression**](http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%204.%20Bayesian%20regression.ipynb)
    - Bayesian fixed effects poisson regression
    - Bayesian mixed effects poisson regression
    
- **Section 5: Bayesian survival analysis**
    - Survival model theory
    - Cox proportional hazard model
    - Aalen's additive hazard model
    
- **Section 6: Bayesian A/B tests**
    - Bayesian test of proportions
    - Bayesian t-test (BEST)

### 왜 베이지안 기법을 배워야 할까요
대학시절 내내 제게 확률론은 멀게만 느껴졌었지요. 빈도주의 기법들 (p-value 뭐 이런거요) 은 뭔가 억지스러웠고 결국에 통계에는 관심따윈 가지지 않게 되었어요.

베이지안 통계학을 우연히 알게되기 전의 이야기지요. 일반적으로 알려진 빈도주의 기법과는 꽤 다른 통계학파입니다.
전 여러 출판물들을 보고 감명받았고, 블로그나 비디오 같은 걸 보게 되었는데 정말 추천할만한 것들이에요. 가령,
- [Doing Bayesian Data Analysis](http://www.amazon.com/Doing-Bayesian-Analysis-Second-Edition/dp/0124058884/ref=dp_ob_title_bk) by John Kruschke
- [Python port](https://github.com/aloctavodia/Doing_bayesian_data_analysis) of John Kruschke's examples by Osvaldo Martin
- [Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) provided me with a great source of inspiration to learn bayesian stats. In recognition of this influence, I've adopted the same visual styles as BMH.
- [While My MCMC Gently Samples](http://twiecki.github.io/) blog by Thomas Wiecki
- [Healthy Algorithms](http://healthyalgorithms.com/tag/pymc/) blog by Abraham Flaxman
- [Scipy Tutorial 2014](https://github.com/fonnesbeck/scipy2014_tutorial) by Chris Fonnesbeck

이 입문서를 제작하게 된 이유는 다음과 같지요. 다른 사람들도 이걸 유용하게 썼으면 좋겠어요.
그리고 위에 나열한 문서들처럼, 이 입문서도 도움이 되었으면 좋겠습니다.
도움이 되기를, 그리고 어떤 지적도 환영합니다.

### Note
This tutorial is actively being worked on. I'm keen to get feedback and welcome ideas/contributions.
