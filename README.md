

**Bitbook Project**
===============




최운영(https://github.com/uyCHOI)<br>
정진솔(https://github.com/smokerJS)<br>
박정아(https://github.com/parkjunga)<br>


---------------------------------------


>**Server-side**<br>
>servlet & jsp 를 이용하여 SNS 형식의 페이지 구현<br><br>

>**DBMS**<br>
oracle Database 11<br>
mybatis 와 Ojdbc6 를 이용<br><br>

>**Tools**<br>
Eclipse<br>
VSCode<br>
Sqldeveloper<br>
Balsamiq Mockups 3<br><br>

>**UI-Framework**<br>
Material Kit<br>
sitemesh-3<br>
Bootstrap4<br><br>

>**FE-lib**<br>
jquery<br><br>

>**Version management**<br>
SourceTree<br>
(https://github.com/uyCHOI/bitbook)<br>

---------------------------------------
![Alt Text](./readMeImg/1_member.jpg)

---------------------------------------

>**정진솔 - 메인 페이지 개발**
>---------
<br>

>ajax 통신을 활용하여 새로고침이 되지 않는 실시간에 가까운 페이지 구현<br><br>

> **핵심기능**<br>
    - 글작성<br>
    - 친구 태그 및 사진 첨부<br>
    - 댓글 및 게시글 좋아요 수정 삭제<br>
    - 검색<br>
    - 실시간 친구목록 확인<br>
    <br>

   
---------------------------------------

>Main View
>---------
>![Alt Text](./readMeImg/2_main.png)
><br><br>
>[![Video Label](./readMeImg/youtube.png)](https://youtu.be/rDBUGfQheao) <br>
>
>**Facebook & Twitter hommage**<br><br>
>웹앱 형식의 SNS 플랫폼을 참고하여<br>
>스크롤페이징 형식의 게시판 구조<br>

---------------------------------------

>Create Post
>---------
>![Alt Text](./readMeImg/3_create.png)
><br><br>
>[![Video Label](./readMeImg/youtube.png)](https://youtu.be/MHfNYveRXSA) <br>
>
>**간단하고 한눈에 보기 쉬운 UI**<br><br>
>친구 태그와 이미지 첨부<br>
>공개범위 설정 등 편리한 기능 제공<br>

---------------------------------------

>Detail and Comment
>--------- 
>![Alt Text](./readMeImg/4_comment.gif)
><br><br>
>[![Video Label](./readMeImg/youtube.png)](https://youtu.be/DBp5a5HnlEg) <br>
>
>**새로고침 되지 않는 다양한 기능**<br><br>
>게시글과 덧글<br>
>수정 및 삭제 좋아요 기능<br>
>태그된 친구의 프로필 확인<br>**(프로필 페이지로 이동)**<br>
>공개범위 표시와 첨부 이미지 확인<br>
>댓글 더보기<br>

---------------------------------------

>Search
>---------
>![Alt Text](./readMeImg/5_search.png)
><br><br>
>[![Video Label](./readMeImg/youtube.png)](https://youtu.be/NGQVilo5bok) <br>
>
>**Order - new . like . comment**<br>
>**Filter - All . Friends . My**<br><br>
>포스트 작성자의 이름 또는 포스트의 내용을 검색할 수 있으며<br>
>전체보기 친구꺼보기 내꺼보기 세가지의 필터와<br>
>최신순 좋아요순 댓글순의 정렬을 지원<br>
>모든 검색조건은 합산방식(And)<br>

>![Alt Text](./readMeImg/6_query.png)<br>

---------------------------------------

>Friends list
>---------
>![Alt Text](./readMeImg/7_friends.png)
><br><br>
>[![Video Label](./readMeImg/youtube.png)](https://youtu.be/KQ5S0dlhjSI) <br>

>**ajax를 이용하여 실시간 친구목록을 구현**<br><br>
>친구들의 활동여부 **on - off** 상태 확인과<br>
>최근 접속시간 표시를 socket 통신 없이 구현<br> (하지만 이는 비효율적입니다)<br>

---------------------------------------

>프로젝트 구조
>---------
>**domain / controller / mapper / utill**<br>
>
>![Alt Text](./readMeImg/8_project.png)

---------------------------------------

>버젼관리
>---------
>**소스트리를 사용하여 수정 및 업데이트가 있을때마다 수시로 관리**<br>
>
>![Alt Text](./readMeImg/9_source.png)<br>

---------------------------------------

***bitbook v 1.0***