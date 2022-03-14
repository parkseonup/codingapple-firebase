# codingapple-firebase

코딩애플 - 당근마켓을 만들며 배워보는 firebase

## firebase 설치

1. 터미널에 install

  ```
  npm install -g firebase-tools@9.23.1
  ```

  - 맥북에서 권한이 없다고하면

    ```
    sudo npm install -g firebase-tools@9.23.1
    ```

2.  로그인

  ```
  firebase login
  ```

3. 현재 경로에 firebase project 생성

  ```
  firebase init
  ```

4. 터미널에 사용할 기능 리스트가 뜨면 스페이스바로 선택해주고 엔터키 눌러야 함

5. 어떤 프로젝트를 추가할건지 물어보는 게 나옴. 마찬가지로 스페이스바 + 엔터키
  - Use an existing project: firebase에 이미 생성해둔 프로젝트를 사용
  - Create a new project
  - 기타 등등

## firebase 사용 방법

- 데이터베이스
  1. 생성하기
  2. 필요한 모드 선택
  3. cloud firestore 위치 선택 (asia-northest3: 서울) - 물리적으로 거리가 가까워야 데이터베이스 사용 속도가 빨라짐
- storage: 이미지 저장소
