## 김지호
시립대에서 한 공부, 프로젝트
## 정보
<details>
  <summary>3학년 1학기에 해야 할 일(방학 포함)</summary>
   &nbsp 1. 토익 990점 달성을 위한 영어 공부</br>
   &nbsp 2. 운전면허 1종 따기</br>
   &nbsp 3. 군사영어 단어 암기</br>
   &nbsp 4. 학점 3점대 후반 ~ 4점대</br>
  
  <summary>임베디드 경진대회 준비 중</summary>
   &nbsp 1. HTML, CSS를 통한 키오스크 구현 </br>
   &nbsp 2. JavaScript 공부 및 키오스크 내에서 사용 </br>
   &nbsp 3. C++ 공부 </br>
   &nbsp 4. 선형대수 공부 </br>
   &nbsp 5. ROS를 통한 Visual SLAM의 구현 </br>
    &nbsp 5-1) ROS 공부 </br>
    &nbsp 5-2) Visual SLAM 공부 </br>
   &nbsp 6. 필요 시 OpenGL 공부도 병
  -------------------------------------------------- </br>
  a) 로봇이 물건 찾는 작동 방식 </br>
   1. 사진을 서버에 올림 </br>
   2. 서버가 이미지를 뿌림 </br>
   3. 이미지에 맞는 물건을 찾는게 목표 - SLAM </br>
   4. 로봇이 지나가는 구간에 찾고자 하는 물건이 없으면, 지도에 표시 - SLAM </br>
   5. 의심되는 물건은 사진을 찍어서 서버에 보내고 위치를 표시 - 카메라 인식 </br>
   6. 로봇이 찾아볼수 없는 부분은 지도에 알려주기 - 상자 같은 서랍 구분이 필요(딥러닝) </br>
  b) 주차/월별 계획 </br>
   3월 5주차 ~ 4월 2주차 </br>
    이미지 처리/딥러닝•머신러닝 </br>
   4월 3주차 ~ 5월 1주차 </br>
    OpenCV: 이미지 처리, SLAM에 이용 </br>
    SLAM: 센서 신호 처리(움직임 추정, 장애물 회피), 그래프 최적화 </br>
    *특이 사항: 4월 말~5월 초에 대회 공지가 올라올 예정이므로 공지 체크할 것. </br>
   5월 2주차 ~ 5월 5주차 </br>
  --------------------------------------------------- </br>
  <img width="863" alt="image" src="https://github.com/DH10032/Teams/assets/155617166/7b859d7a-5345-4ada-b6a8-235f7b1e94e1"> </br>
  처리 순서는 (frondend - > backend) - > Map representation(맵 작성) </br>
  frondend를 먼저 끝낸 후 backend를 진행하면 어떨까 생각. (협의 후 결정 예정) </br>

 1) Data Acquistion, Visual odometry, Loop closure detection - > frondend </br>
 Data Acquisiton (데이터 획득): 카메라/라이다 같은 센서로부터 정보 획득 (+데이터로부터 노이즈 제거 필요) </br>
 Visual odometry (시각적 주행 거리 측정): 데이터 특정 추출 -> 상대적 움직임 예측 </br>
 Loop closure detection (루프 폐쇄 검출): 방문한 위치인지 판단. </br>
2) Backend optimization(최적화) - > backend </br>
  
<details>
  <summary>회로 및 라즈베리</summary>
  우분투 20.04로 설치 완
  
  모터는 dc모터+드라이버 (배달중) </br>
  배터리는 9v짜리 건전지 </br>
  카메라는 미정 </br>
  
</details>

  
</details>

<details>
  <summary>공간인식</summary>
  
  1. 아두이노 실내 위치추적 모듈(오차 10cm내외) - DWM1000 모듈
  
  2. [SLAM 방식](https://hjdevelop.tistory.com/15/)
     
  SLAM 방식
    <details>
      <summary>프런트 엔드</summary>
    </details>
  
  <details>
      <summary>백 엔드</summary>
    </details>
  
</details>

