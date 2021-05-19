# Model Pivot Resetter

- UPM(Unity Package Manager) 형태로 작성

<br>

# How To Import

`[Window]` - `[Package Manager]` - `[+]` - `[Add package from git URL]` - `https://github.com/rito15/Unity-Model-Pivot-Resetter.git`

<br>

# Summary

- 모델링 파일을 유니티로 가져올 때 동작하는 애셋포스트프로세서
- 모델의 회전과 위치를 리셋한다.
- 모델의 정점 위치를 모두 계산하여, 피벗이 모델의 중심 하단으로 오게 한다.

<br>

# How To Use

- 스크립트를 유니티 프로젝트 내에 넣는다.

- [Window] - [Rito] - [Model Pivot Resetter] - [Activated]를 체크한다.
  - 체크 해제되어 있을 경우 동작하지 않는다.

![image](https://user-images.githubusercontent.com/42164422/110126112-6dfb7900-7e07-11eb-8145-eb635f7b8761.png)

- 임포트 할 때마다 대화상자를 통해 선택하게 하려면<br>
  [Window] - [Rito] - [Model Pivot Resetter] - [Show Dialog]에 체크한다.

![image](https://user-images.githubusercontent.com/42164422/110122641-3559a080-7e03-11eb-8db9-4d3247738a35.png)

<br>

# Preview

## [1] 기본


- 모델 임포트, 하이라키로 가져왔을 때
  - 트랜스폼 위치, 회전, 크기, 피벗 모두 제각각이다.

![image](https://user-images.githubusercontent.com/42164422/110127359-e282e780-7e08-11eb-8fbc-9c7fe9debc58.png)


- 이 상태에서 트랜스폼을 리셋한 경우
  - (0, 0, 0) 위치로 와서 드러누워 버린다. (기존 rotation.x 값 : 270)

![image](https://user-images.githubusercontent.com/42164422/110122836-7a7dd280-7e03-11eb-96e0-ad1baf381101.png)


<br>

## [2] Pivot Resetter 사용

- 트랜스폼 위치, 회전, 크기 모두 기본 값으로 정상 리셋된다.

- 피벗 위치는 모델의 중앙 하단으로 변경된다.

![image](https://user-images.githubusercontent.com/42164422/110123018-bd3faa80-7e03-11eb-9c25-25f4d8e3fe58.png)

