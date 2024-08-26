# 대구 버스정류장 위치표기 프로젝트

---

## 개요
대구 시청에서 근무하면서 **'지도 상에 대구 버스정류장 위치표기'** 업무를 할당받았고, 이를 **HTML과 네이버 지도 API**를 활용하여 구현하였습니다.

---

## 전처리 진행과정
제공받은 파일은 엑셀 파일 하나로, 버스정류장 세부사항이 기재된 총 8개 행정구역 (예: 중구, 서구, 달서구 등)의 시트로 구성되었습니다.

구글 코랩 환경에서 해당 파일의 **'버스정류장 이름'** 과 **'해당 정류장의 주소'** 열을 추출한 뒤, 네이버 지오코드 API를 활용해 위도와 경도로 변환했습니다.

![전처리 과정 이미지](https://github.com/user-attachments/assets/4493962f-e7f8-43ff-9765-89b313f2cfc5)

---

## 동작 설명
- 각 행정구역 버튼을 누르면 해당 행정구역에 속한 버스정류장의 위치를 지도상에 표시합니다.
- **'모니터링'** 버튼: 관심을 두고 있는 특정 버스정류장만을 지도에 표시합니다.
- **'스마트쉘터'** 버튼: 스마트쉘터가 설치된 버스정류장을 지도에 표시합니다.
![동작 설명 이미지](https://github.com/user-attachments/assets/88ab0028-8b9a-4be0-a736-cd4ede7d2554)


---

## 개발 고려사항
시청 직원분들은 CS 지식이 전무하기 때문에 최대한 파일 구성을 쉽게 만들어 제공해야 했습니다.  
따라서 **HTML 파일 하나에 모든 소스코드**를 포함시켜 하드코딩 방식으로 구현했습니다.

---

## 결과
시청 직원분들의 빠른 의사결정 프로세스에 도움을 줄 수 있었습니다!! 😊

![결과 이미지](https://github.com/user-attachments/assets/caba7b91-7549-4150-9ae4-f0fa0fd57b3e)

---

