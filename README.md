# state variables
input -> states(system) -> output 과정을 거친다.

#example 1 : spring-mass-damper system

![image](https://github.com/user-attachments/assets/1bae04f5-009f-4fab-a934-87bbecdb97d8)

x1(t) = y(t) , x2(t) = dy(t)/dt에서 미분방정식을 풀면 1) dx1(t)/dt = x2(t), 2) dx2(t)/dt = -b/m*x2(t)+k/mx1(t)+1/mr(t)

#example 2 : R-L-C circuit system

![image](https://github.com/user-attachments/assets/9e3d4904-edeb-4aa8-a415-233d2a739afa)

x1(t)=vc(t), x2(t)=il(t)이소 kcl, kvl을 정리하면 

1) dx1(t)/dt=1/c{-x2(t)=u(t)} 2) dx2(t)/dt=1/L{x1(t)-rx2(t)}, y(t)=rx2(t)

#1st order state differential equation

![image](https://github.com/user-attachments/assets/adffb3b2-9f27-4819-a504-030007fec4f5)

transition from initial state와 effect of input을 구할 수 있다. 

#state vector and state space equation

위에서 구함 R-L-C의 방정식을 다음과같이 벡터로 표현할 수 있다.

![image](https://github.com/user-attachments/assets/b1636bc6-8e74-4fb0-8c7a-948aeed6c072)

