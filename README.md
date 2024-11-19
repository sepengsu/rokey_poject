# 2024 두산 로보틱스 팀 프로젝트 
![image](https://github.com/user-attachments/assets/ff7f6d89-8bcd-4715-bbbd-9d4be2b6c190)

![image](https://github.com/user-attachments/assets/53f0cbc9-a021-48ad-903a-322c401606b5)

1. 기간: 2024.11.05 ~ 12.31

## 설치 방법 및 git 사용법 간단히 
[가이드라인](SETUP.md)
#### [Week1 주행1: 서비스 로봇 및 관제 시스템 개발](https://github.com/sepengsu/rokey_week1_ws)
#### [Week2 협동1: DART 플랫폼(두산로보틱스)을 활용한 협동로봇 동작 운영 실습](https://github.com/sepengsu/rokey_week2_ws)
#### [Week3 협동2: ROS-2 프로그램을 활용한 협동로봇 동작 운영 실습](https://github.com/sepengsu/rokey_week3_ws)

### 꿀팁 
https://github1s.com/  
github에서 이걸로 바뀌면 vscode 형식으로 볼 수 있음 

```
ros2 service list | grep AAA  
```
이 코드는 특정 서비스의 리스트들을 확인해주는 방법 
```
ros2 service type AAA
```
이 코드는 특정 서비스의 타입들을 확인하여 어떤 것들로 call할지 확인한다.

```
ros2 service call AAA BBB "{}"
```
이거로 call하면 됨 
