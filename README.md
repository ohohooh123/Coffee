# Coffee Team 필독사항

## 항상 pull 먼저 해야합니다 !!!
각자 개인 branch 생성후 작업 진행!!
본인 branch 에서 작업후 커밋, push 한 뒤에 팀장한테 merge요청!!
팀장이 merge 승인한걸 확인하면 local branch 삭제
브랜치를 삭제하는 이유는 원본 저장소에 Merge가 완료되면 작업공간이 더이상 필요 없으므로 삭제한다.

pull -> git branch [사용할 브랜치명] git switch [사용할 개인브랜치] -> 작업 -> add, commit -> git push origin [사용할 개인브랜치]
-git push하는 과정에서 오류가 뜰 경우 origin +main으로 해볼것.

```
 $ git pull origin main
 $ git add .
 $ git commit -m " 커밋내용 "
 $ git push origin [branch name]
 
 push error시에 바꿔봐야 할 코드
 $ git push origin +[branch name]
 
```




# OPEN API SITE

- 공공데이터 포털 https://www.data.go.kr/
- 부산 공공데이터 https://data.busan.go.kr/index.nm;jsessionid=2BE87469E6B9D2DEEBB25BA45DAF2C8D
- KAKAO OPEN API https://developers.kakao.com/

# Tools
<div align=center>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=&logoColor=white"/>
  <img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/vsCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tomcat-F8DC75?style=flat-square&logo=apachetomcat&logoColor=white"/>
  <img src="https://img.shields.io/badge/Eclipse-2C2255?style=flat-square&logo=eclipseide&logoColor=white"/>
  <img src="https://img.shields.io/badge/json-000000?style=flat-square&logo=json&logoColor=white"/>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/>
  <img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/git-F05032?style=flat-square&logo=git&logoColor=white"/>
</div>


## 팀소개

#### 팀장 : 김경돈  JS, API, HTML ,CSS
#### 팀원 : 김경목  DB, API, Erwin, HTML ,CSS
#### 팀원 : 이아진  JS, API, HTML ,CSS
#### 팀원 : 장연서  JS, API, HTML, CSS
<br>

## 화면구현

![1](https://github.com/ohohooh123/ohohooh123/assets/45931408/92177f48-824f-420d-bede-e1a4fb3feb3b)

<p>한국어, 영어, 일본어, 중국어 4개 언어를 사용가능한 메인 페이지</p>

![2](https://github.com/ohohooh123/ohohooh123/assets/45931408/3688f461-d892-45b3-8b50-1da988e384a3)

<p>구별 맛집 검색 가능</p>

![3](https://github.com/ohohooh123/ohohooh123/assets/45931408/af73d109-fe37-4081-bc5b-2a84f71369f5)

<p>공공 포털의 Open API는 다국어를 지원함. 영어 버전의 축제 검색 화면</p>






