# DE:home 
> 아래의 글을 누르면 해당 홈페이지로 이동합니다. <br>
> <a href="https://www.mydehome.com/dehome/main/mainpage">디홈으로 이동</a><br>
> test계정 - test1/test1

## 프로젝트명 : 디홈(DE:home)
Decorating your Home

> 그린 컴퓨터 아카데미 자바 과정 이수 하면서 만든 두번째 팀 프로젝트입니다.

<strong>1팀 구성</strong><br>
1. <strong>김준형</strong>(본인)<br>
2. 김경윤<br>
3. 박소은<br>
4. 권연진<br>
5. 이동현<br>

## 개발기간
2021/06/01 ~ 2021/07/04(33일)

## 프로젝트의 목적<br>
### 10대 후반에서 30대 후반까지의 MZ세대를 중심으로 중고거래는 하나의 문화로 자리잡고 있습니다.<br>
### 그와 더불어 코로나로 인해 세상은 많은 것이 변했습니다.<br>
### 집콕이 장기화됨으로 인해 집 안에 머무는 시간이 많아졌고, 자연스레 인테리어에 대한 관심도가 높아졌습니다.<br><br>

### 이에 인테리어와 중고거래를 합쳐 인테리어 제품을 중고로 거래하고,<br>
### 실제 인테리어 업체와 연결될 수 있는 <br>
### 종합 플랫폼 웹을 개발 해보았습니다.<br><br><br>

## 사용된 기술 스택

### 프레임워크
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white"/>&nbsp; 
### 언어
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/>&nbsp; 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>&nbsp;
### 관련 기술
<img src="https://img.shields.io/badge/JQuery-0769AD?style=flat-square&logo=JQuery&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>&nbsp; 
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3#&logoColor=white"/>&nbsp; 
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
### DB
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>&nbsp;
### 배포
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=AmazonAWS&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=Ubuntu&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=ApacheTomcat&logoColor=white"/>&nbsp;
<br><br><br>

## 홈페이지메인화면
![image](https://user-images.githubusercontent.com/74701876/125226183-8aef0e00-e30b-11eb-8b1f-b8307b2db358.png)
<br><br><br>

## 데이터베이스 ERD(ERDCloud로 작성)
![erd](https://user-images.githubusercontent.com/74701876/125284062-f78dfb00-e353-11eb-83ea-0fc0e30e179b.png)


<br><br><br>
## 내가 수행한 작업
> <b>인테리어 팁</b> - 인테리어 팁(카테고리 별 작성, 사진, 썸네일, 북마크)<br>
> <b>마이페이지</b> - 나의 거래(판매,구매), 내가 작성한 글(인테리어 팁, QNA), 북마크 <br> 
> <b>ERD<b> - ERDCloud로 ERD 제작<br>
<br><hr>
  
# 내가 수행한 작업 설명

## 인테리어 팁 
> - 인테리어 팁 메인 페이지 : 카테고리 별 전체 출력, 썸네일, 북마크(AJAX 사용) 표시
> - 인테리어 팁 카테고리 별 페이지 : 썸네일, 북마크(AJAX 사용) 표시
> - 인테리어 팁 작성 : 사진 업로드(FTP를 사용해서 ubuntu 가상 서버 사용)

### 인테리어 팁 메인 화면
  
![인테리어팁메인](https://user-images.githubusercontent.com/82127619/128460228-f40f09dd-2c3f-4efa-8d73-a7fe88f7ef9d.png)
![북마크](https://user-images.githubusercontent.com/82127619/128460494-cb12fd35-dde6-4ca9-bd7b-ae27aa9440bc.png)

 - 카테고리 별 인테리어 팁 4개씩 노출
 - 더보기 버튼으로 각 카테고리 별 인테리어 팁 화면으로 이동
 - 우측 하단 북마크 등록 여부 확인 가능
 - 조회수 순으로 출력
  
### 인테리어 팁 카테고리 별 화면
  
![카테고리별](https://user-images.githubusercontent.com/82127619/128460388-ce352022-ae25-49ac-9312-4977f05c499d.png)
  
- 상단 헤더 카테고리 선택시 들어옴
- 팁 별 제목, 조회수, 스크랩수, 북마크여부, 썸네일 출력 
  

### 인테리어 팁 작성
  
![팁작성](https://user-images.githubusercontent.com/82127619/128461343-17b63085-cec7-40a5-b363-557d04d6aaa2.png)
![카테고리](https://user-images.githubusercontent.com/82127619/128461350-4fc849a1-1958-4e9c-9e2f-a44e17a1a975.png)

- 카테고리 선택, 제목, 사진, 내용 작성
  
### 인테리어 팁 상세보기
  
![팁상세](https://user-images.githubusercontent.com/82127619/128461477-a2d7c55f-3d86-4b8b-9c06-17f28f0145d8.png)
![북마크여부](https://user-images.githubusercontent.com/82127619/128461707-fbf9b3fc-5170-419a-acc9-591ded07e72f.png)
![북마크해제](https://user-images.githubusercontent.com/82127619/128461710-83c3fa89-ce05-4969-9b46-7d6fca9b8df5.png)

- 작성자 조회수 증가 X
- 유효성 검사 후 북마크 해제
  
### 마이페이지 
  
![작성한팁](https://user-images.githubusercontent.com/82127619/128462496-e94e0940-12bd-4654-8fd1-1fcf7c19c5e7.png)
![마이북마크](https://user-images.githubusercontent.com/82127619/128462506-a388533b-bda7-43a2-8425-bc5e397b74d4.png)
![내QNA](https://user-images.githubusercontent.com/82127619/128462509-d4375aed-6677-4272-8b3b-ba01baedbb85.png)

  
- 나의 활동사항 ( 인테리어 팁, QNA, 북마크 등) 확인 가능
  
  
## 마무리

  
#### 실제 배포 담당은 아니었어서 실제 배포를 처음부터 끝까지 해보지 못한 점이 아쉽고, 다음번엔 직접 호스팅 및 배포를 해보고싶다
#### 1차 프로젝트에서는 학원에서 배웠던 jsp만 활용했기 때문에 크게 오류가 생겼던 적이 없었지만 이번 스프링을 활용한 프로젝트를 진행하면서 많은 오류들을 경험했고 그 덕분에 팀원들과의 커뮤니케이션으로 오류에도 당황하지 않고 해결하는 법을 터득했다
#### 1차 프로젝트보다 함께 작업하는 팀원들의 증가로 서로 중간보고 혹은 겹치는 개발 파트 등에 대해 기존에 생각했던 것 보다 훨씬 더 자세하고 반복적인 커뮤니케이션이 필요하다는 것을 알게 되었다
  
  
### 아쉬운점
- AWS를 사용해서 배포를 했으나, 직접 참여하지 못해 전반적인 이해를 하지 못했다.
- 시간이 부족해서 조금더 완벽한 프로그래밍을 못한게 아쉽다.

### 1차 프로젝트보다 발전한 부분
- 이전 1차 프로젝트에선 게시판에 단순하게 글만 작성이 가능했다면 이번 프로젝트에서는 사진 업로드 할 수 있는 부분 등의 발전이 있었다.
- jsp로만 작업할 당시에는 수많은 jsp페이지와 그곳을 넘나들면서 작업이 실행되었지만 AJAX를 활용하면서 비동기 방식으로 처리하면서 더욱 깔끔하고 빠르게 구현할 수 있었다.
  
  
  
  
