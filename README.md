# ALCon (Automatic Light Controller)

- project period : 2018.4.1 ~ 2018.11.27

<br>

### 프로젝트 소개 밎 주요기능
- 조명기기 이상의 역할을 수행할 수 있도록 도와주는 탈부착형 자동 조명 제어장치
- 조도에 따라 빛의 세기가 자동 조절이 가능하며 일정 조도를 유지할 수 있는 조명장치
- 사용자 필요에 따라 선택 사용이 가능하도록 기본형과 고급형으로 나누어 개발


<img src="https://github.com/user-attachments/assets/51af49c2-2b04-44ac-a923-394e2d8bfa07" width="750" height="358"/>

<br>
<br>
<br>

### 작품의 특징 및 장점
- 플러그에 단순 장착만으로 조명을 제어하는 기능을 탭재하여 사용자가 불편함을 느끼지 않도록 함
- 고급형 모델의 경우 어플리케이션을 통해 조작이 가능하며 일정 거리 내에서 원격조작을 할 수 있음
- 어플리케이션 내 타이머 및 예약기능, 취침기능, 모닝콜 기능 등을 활용할 수 있음
- 이외에도 하드웨어 자체로 조도감지를 통한 자동 전원 on, off 기능과 물리적인 밝기 조정 기능 등이 있음

<br>

### 프로젝트 개발환경
#### SW 개발환경
- 안드로이드 OS (5.0.1) : 앱 구동 확인 등
- Arduino IDE : 프로그램 편집 및 컴파일, 업로드
- Cadence OrCAD 15.6 : 하드웨어 내 PCB 제작을 위한 artwork 작업
- Allegro PCB Designer : OrCAD 내 기본 부품 외 부품 파일을 생성
- 개발 언어 : Arduino C, Python

#### HW 구성장비
- NodeMCU : RTC를 활용할 수 있는 크기가 작은 MCU
- CDS, PIR. BLE 등 기능 구성용 센서
- SSR, SMPS 등 전원 공급 및 전력 변환장치
- 여러종류의 조명기기 : ALCon 테스트용

<br>

### 결과물
[결과물 영상](https://youtu.be/CQbYO37CFTA)
