# Html_1026  
  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/197915775-ad8c8f12-1971-4606-a16a-911bc1af7dc8.png)
  
  
  
  
  
**파일명.확장자** 
  
  
  
  
  
  
  
  
```
<!DOCTYPE html> <!--문서를 도큐멘트라고하고 !가 맨앞에있다는것은 HTML5버전의미
                    버전별로 지원하는 태그가 달라 버전을 표기하는것이 좋다 -->
<html lang="en"> <!--문서의 언어형식 (현재는 영어)-->
<head> <!--화면에 표시되지 않고 문서에 대한 정보를 기록하는곳-->
    <meta charset="UTF-8"> <!--문자코드 형식 한글을 표현하는 방식은 EUCKR ,UTF8
                                                            EUCKR:    한국에서만 사용 3바이트로 한글 저장
                                                            UTF8:    전세계 공통-- 2 바이트-->

    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<!---주석
1.용어 : 태그 <tag></tag> 태그의 시작과 끝
태그의 뒤는 속성
2.태그는 부모와 자식의 관계가 있으므로 부모태그안에 태그를 작성할때는 스페이스바 기억하시오
-->
<style>
    h1{                     /*주석이렇게 씀 css부분*/
        color: rebeccapurple;
        background-color: antiquewhite;
    }


</style>

<script>
    
    function aa(){       //여기는 주석 이렇게 자바스크립트 부분.동적화면 구현할 수 있음
        var a =20;
    //자료형 선언문 구현문 메서드-자바의 메서드(정의와 호출,매개변수 전달 했는가?-리턴값을 받는것)
        alert("당신의 나이는?")
        let b = bb(10);
        var c = "입니다";
        a = a+b;
        alert(a+c);
        document.write(a);
    }
    function bb(aa){
        return aa+90;
    }
</script>

<body> <!---화면에 표시할 문서를 작성하는곳-->
    <h1>첫번째 만드는 웹 문서</h1>
    <input type="button" value="버튼" onclick="aa()">  <!--함수호출부-->
</body>
</html>
```
  
  
  
   
   
   
   
   
   
   
   
   
   
   
   
  
  
```
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>하용잉</title>
</head>
<body>
    
    <h1>공부하기 메뉴</h1><br>
    <a href ="#a">개발환경</a><br>
    <a href ="#b">UI</a><br>
    <a href ="#c">html</a><br>
    <a href ="#d">프로그램 설치하기</a><br>
    <a href ="#e">html 기본구조</a><br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <h2 id="a">1.개발환경 (서버와 클라이언트 구조의 웹 프로그램)</h2>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <h3 id="b">2.UI 제공화면 공부 - html<br>
    프로그램 : visual Studio Code<br>
    언어형식 : UTF-8(eunkr도 같이 공부해 두세요)<br>
    </h3>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <h4 id ="c">3.html 개발환경 구성<br>
        프로그램 : visual Studio Code<br>
        언어형식 : UTF-8(eunkr도 같이 공부해 두세요)<br></h4>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <h5 id="d">4.프로그램 설치 후 한글팩 설치, live server 설치,<br>기본브라우저 크롬으로 설정<br></h5>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <h2 id="e">5.html 기본구조<br>태그와 태그의 속성 중심으로 공부한다. <br>어떤 태그인지 속성은 있는지</h2>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <ul>
        <li>웹프로그램의 이해
            <ol>
                <li>개발환경</li>
                <li>백앤드와 프론트</li>
            </ol>
        </li>
        <li>프로그램의 이해
            <ol>
                <li>UI</li>
                <li>html 이해</li>
                <li>프로그램 설치하기</li>

            </ol>
        </li>
    </ul>

    <img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fimgnews.naver.net%2Fimage%2F5717%2F2022%2F09%2F02%2F0000010564_001_20220902163203006.jpg&type=a340">
    <p></p><img src="./main.jpg">
    <table border="1">
        <tr>
            <th colspan="6"><strong>한국의 차</strong></th>
        </tr>
        <tr>
            <th rowspan="6">뿌리차</th>
            <td>인삼차</td>
            <th rowspan="9">과일차</th>
            <td>수정과</td>
            <th rowspan="5">잎차</th>
            <td>뽕잎차</td>
            
        </tr>
        <tr><td>당귀차</td>
            <td>유자차</td>
            <td>감잎차</td>
        </tr>
        <tr><td>생강차</td>
            <td>구기자차</td>
            <td>솔잎차</td>
        </tr>
        <tr>
            <td>칡차</td>
            <td>대추자</td>
            <td>국화차</td>
        </tr>
        <tr>
            <td>둥굴레차</td>
            <td>오미자차</td>
            <td>이슬차</td>
        </tr>
        <tr>
            <td>마차</td>
            <td>매실차</td>
            <th rowspan="4">기타</th>
            <td>두충차</td>
            
        </tr>

        <tr>
            <th rowspan="3">곡물차</th>
            <td>보리차</td>
            <td>모과차</td>
            <td>영지버섯차</td>
        </tr>
        <tr>
            <td>옥수수차</td>
            <td>산수유차</td>
            <td>귤강차</td>
        </tr>
        <tr>
            <td>현미차</td>
            <td>탱자차</td>
            <td>쌍화차</td>
        </tr>

    </table>





</body>
</html>
```
  
  
  
  
  
