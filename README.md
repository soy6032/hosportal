# hosportal
스프링부트를 이용한 병원 예약 웹 프로젝트
<h2>프로젝드 소개</h2>
<p>여러 종류의 병원을 한눈에 볼 수 있고, 병원에서 추가로 제공하는 정보와 이벤트, 이용자들이 남긴 리뷰를 실시간으로 보여줌으로서 회원들이 합리적인 병원 선택을 돕고 병약예약과 병원 문의을 간편하게 할 수 있기를 돕기 위한 프로젝트입니다.</p><br>
<p>또한 병원 회원도 사이트를 이용해 이벤트를 등록하거나 좋은 후기들로 병원 홍보 효과를 볼 수 있습니다</p>
<h2>개발일정</h2>
<p>2021.04.05 ~ 2021.04.26</p>
<h2>팀구성</h2>
<p>박소영, 김동훈, 양수아, 이정은</p>
<h2>팀원별 역활</h2>
<ul>
  <li>공통: 프로젝트 기획</li> 
  <li>박소영: DB설계, 회원가입, 로그인, 예약, 문의, 마이페이지, 페이징, UI 다자인</li>
  <li>김동훈: 이미지 업로드, 검색, 오류 수정</li>
  <li>양수아: 이벤트 게시판, 커뮤니티 게시판, 댓글, 페이징</li>
  <li>이정은: 프로필, 마이페이지</li>
</ul>
<h2>개발환경</h2>
<ul>
  <li>Programming Language: JAVA, HTML, Javascript</li>
  <li>Server : Tomcat9</li>
  <li>DB: Mysql</li>
  <li>Framework/flatform: Spring Boot, bootstrap, jQuery, Ajax, mybatis</li>
  <li>Tool: STS, Mysql Workbench</li> 
  <li>API:  Kakao Developer</li>
</ul>
<h2>주요기능</h2>
<h3>메인</h3>
<p>메인 페이지에서 최근 입점 병원, 최대 조회수 병원, 최신 리뷰 병원을 순서대로 5개씩 미리 확인이 가능하도록 구현하였습니다.<br>
  하단에서 이벤트와 커뮤니티 게시글을 최신순으로 미리보기가 가능합니다.
</p>
<img src="https://user-images.githubusercontent.com/48235429/116366713-8c975280-a841-11eb-8a54-e666378e2637.png">
<h3>로그인</h3>
<P>개인회원과 병원회원은 각각 다른 폼에서 로그인되고 로그인 성공 시 각각 다른 페이지로 이동됩니다.</p>
<img src="https://user-images.githubusercontent.com/48235429/116367059-e435be00-a841-11eb-9c89-95a54895aa59.png">

<h3>회원가입</h3>
<P>개인회원과 병원회원은 각각 다른 회원가입 폼으로 회원가입 됩니다.<br>
  Ajax를 활용하여 아이디 중복 검사를 합니다.<br>
  다음에서 제공하는 API를 이용하여 주소 검색 기능 제공 합니다.<br>
  이미지를 선택하여 프로필사진을 등록할 수 있습니다.
</p>
<img src="https://user-images.githubusercontent.com/48235429/116368626-80ac9000-a843-11eb-9694-dabb2f145c8a.png">

<h3>병원 목록</h3>
<P>
  병원은 진료과목별, 지역별로 검색 할 수 있습니다.<br>
  Ajax를 활용하여 버튼을 클릭하면 실시간으로 그에 맞는 병원을 보여줍니다.<br>
</p>
<img src="https://user-images.githubusercontent.com/48235429/116369657-953d5800-a844-11eb-99dd-1e82c413bcc3.png">
