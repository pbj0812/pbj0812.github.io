---
title: "머신러닝 AtoZ"
date: 2018-12-18 11:18:28
categories: jekyll update
---

# A

# B
## Bayes' Theorem
 - 데이터에 대한 적절한 가정이 있다면 관측한 데이터만을 사용하는 것 보다 더 우수한 parameter estimation을 가능하게 함.
 
[참조](http://sanghyukchun.github.io/58/)

## Bernoulli Distribution
 - 동전 던지기
 
[참조](http://arkainoh.blogspot.com/2017/10/parametric.learning.maximum.likelihood.estimation.html)

# C
## Conditional Entropy
 - 조건부 확률 p(x&#124;y)의 개념을 Entropy로도 확장하여 적용한 것
 - y라는 사건이 일어났을 때, x의 불확실성을 측정한 것
 - H(X&#124;Y) = H(X,Y) - H(Y)
 
 [참조](http://newsight.tistory.com/119)
## Cross Entropy
 - Joint Entropy : 하나의 확률 분포 p에 대해서 X와 Y 두 개의 사건이 갖는 정보량
 - Cross Entropy : 두 개의 확률 분포 p와 q에 대해 하나의 사건 X가 갖는 정보량
 
<figure>
	<img src="{{ '/assets/img/fig_cross_entropy.png' | prepend: site.baseurl }}" alt=""> 
	<figcaption>Cross Entropy</figcaption>
</figure>
 
 [참조](http://newsight.tistory.com/119)
# D

# E
## EM 알고리즘
 - 모델 파라미터의 초기값을 임의로 설정(θ^old 값)
 - θ^old  값을 이용하여 파라미터의 새로운 θ^new 값을 얻기 위해 방정식의 우변을 계산
 - θ^old 와 θ^new 의 차이가 0에 가까워지면 알고리즘을 멈춤
 
[참조](http://iskim3068.tistory.com/52)

## Entropy (Information Entropy)
 - 기호 : H
 - 단위 : 비트
 - 모든 결과물이 동등하게 나오는 최대치
 - 정보의 엔트로피가 떨어진다면 결과물을 추측하기 위한 질문을 적게 해도 된다는 것을 뜻함

<figure>
	<img src="{{ '/assets/img/fig_entrophy.png' | prepend: site.baseurl }}" alt=""> 
	<figcaption>Entropy</figcaption>
</figure>

[참조1](https://ko.khanacademy.org/computing/computer-science/informationtheory/moderninfotheory/v/information-entropy)

[참조2](http://untitledtblog.tistory.com/119)

# F

# G
## GMM (Gaussian Mixture Model)
 - k개의 정규분포를 섞어서 만든 모델
 - 기존의 가우시안 확률분포는 하나의 그룹으로 뭉쳐있는 형태만을 표현가능하다는 제약이 있음
 
[참조1](https://3months.tistory.com/154)
[참조2](http://iskim3068.tistory.com/52)

# H

# I

# J
## Joint Entropy
 - 확률 p(x,y)에 대한 엔트로피, 교집합의 엔트로피
 - x와 y가 서로 독립이라면, H(x, y) = H(x) + H(y)

<figure>
	<img src="{{ '/assets/img/fig_joint_entrophy.png' | prepend: site.baseurl }}" alt=""> 
	<figcaption>Joint_Entropy</figcaption>
</figure>

[참조](http://newsight.tistory.com/119)

# K
## KL Divergence (=relative entropy, information gain)
 - 두 확률 분포 p,q 간의 거리를 측정하는 방법
 - p(x)와 xq의 값이 항상 같을 경우, 두 분포간의 거리가 0인 것을 의미

<figure>
	<img src="{{ '/assets/img/fig_kl_divergence.png' | prepend: site.baseurl }}" alt=""> 
	<figcaption>KL Divergence</figcaption>
</figure>
 
[참조](http://newsight.tistory.com/119)
# L
## Likelihood
 - 가능도
 - 확률분포함수의 y값
 - 셀 수 있는 사건 : 가능도 = 확률
 - 연속 사건 : 가능도 ~= 확률, 가능도 = PDF 값

[참조](http://rstudio-pubs-static.s3.amazonaws.com/204928_c2d6c62565b74a4987e935f756badfba.html)

# M
## mAP (mean Average Precision)
[참조](https://hoya012.github.io/blog/Tutorials-of-Object-Detection-Using-Deep-Learning-how-to-measure-performance-of-object-detection/)
## MAP (Maximum a Posteriori Estimation)
 - θ가 주어지고, 그 θ에 대한 데이터들의 확률을 최대화하는 것이 아닌, 주어진 데이터에 대해 최대 확률을 가지는 θ를 찾음

[참조](http://sanghyukchun.github.io/58/)
## MLE (Maximum Likelihood Estimation)
 - 최대 가능도 추정량
 - 주어진 데이터들 만을 토대로 parameter estimation 하는 방법
 - 가장 간단한 parameter estimation method이지만, observation에 따라 그 값이 너무 민감하게 변함

[참조](http://sanghyukchun.github.io/58/)
## Multinomial Distribution
 - 확률변수 x가 다항분포를 따름
 
[참조](http://arkainoh.blogspot.com/2017/10/parametric.learning.maximum.likelihood.estimation.html)
## Mutual Information
 - X와 Y가 서로 독립인지 아닌지에 대한 정도를 정보량으로 측정한 것
 - X,Y 변수가 서로에 의해서 영향받는 정도를 정보량으로 측정한 
 
[참조](http://newsight.tistory.com/119)

# N

# O

# P
## PDF(Probability Density Function)
 - 확률밀도함수
 - 그래프에서 특정 구간에 속한 넓이는 특정 구간에 속할 확률과 같음

[참조](http://rstudio-pubs-static.s3.amazonaws.com/204928_c2d6c62565b74a4987e935f756badfba.html)

# Q

# R

# S

# T

# U

# V

# W

# X

# Y

# Z
.
