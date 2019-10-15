onda 가상환경을 이용하여 실행했습니다.

## conda 가 설치되어 있을 경우 

 - windows : Anaconda prompt 실행(관리자권한)

 - Linux : 따로 실행할거 없음

## 가상환경 생성

conda create -n [가상환경명] python=3.7


## 가상환경이 생성되면 가상환경을 실행시켜줘야 함

conda activate [가상환경명]

## 이제 pytorch 설치

conda install pytorch torchvision cpuonly -c pytorch

## 나머지 필요한거 설치(설치 안되어 있을 경우)

pip install numpy matplotlib

## Tensorboard 설치 

conda install -c conda-forge tensorboardx

## Tensorboard 실행

- working directory 에 가서 실행

tensorboard --logdir=[경로]

## 크롬이나 인터넷익스플로러를 통해 접속

- 로컬 컴퓨터에 설치 했을 경우 : http://127.0.0.1:6006

- 서버컴에 설치 했을 경우 : http://주소:6006

