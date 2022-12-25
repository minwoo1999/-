## 회의실예약 및 관리 프로그램
dd
###  사용기술 및 라이브러리
* spring boot
* oracle
* thyleaf

### version 및 structure
* jdk 11
* mybatis
* mvc


## 프로젝트에서 수행한 역할 및 깨달은 점

#### doFilter 필터처리

* doFilter를 사용하여 로그인을 하지않은 사용자는 해당페이지에 접속못하게 처리하였습니다.

#### webConfig를통한 외부이미지 업로드처리

* webConfig를 통해서 임의의 외부경로를 설정하며, 외부경로로 이미지를 업로드를 하였습니다.

#### 백엔드 Mutlipart 기반 업로드 구현

* 클라이언트에서 원본 이미지, 비디오 및 파일들을 서버로 직접 올리기 때문에, 파일을 나누어 전송하는 Mutlipart 방식으로 파일 업로드를   구현하였으며, 이를 통해 서버에 한꺼번에 많은 트래픽이 가해지는 것을 방지하였습니다.



회의실 예약 이미지

![image](https://user-images.githubusercontent.com/79193811/200159743-a553173f-fe0f-4400-8da1-8d3593afba01.png)


