<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>테이블 연습1</title>
</head>
<body>
  <h1>테이블 연습1</h1>
  <table border="1">
    <caption>2023년 식비</caption>
    <tr>
      <th>월</th>
      <th>일</th>
      <th>금액</th>
    </tr>
    <tr>
      <th rowspan="2">3월</th>
      <td>1일</td>
      <td>1,000</td>
    </tr>
    <tr>
      <td>2일</td>
      <td>2,000</td>
    </tr>

    <tr>
      <th colspan="2">합계</th>
      <td>3,000</td>
    </tr>
  </table>
  
</body>
</html>


<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>테이블 연습 2</title>
</head>
<body>
  <h1>테이블 연습2</h1>
  <table border="1">
    <caption>여름이온다 그림책 안내</caption>
    <tr>
      <th colspan="3">그림책 소개</th>
    </tr>

    <tr>
      <th colspan="3">여름이 온다</th>
    </tr>
    
    <tr>
      <th rowspan="3"><a href="https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=276691731" target="_blank"><img src="./images/여름이온다표지.jpg" alt="여름이 온다 책 표지"></a></th>
      <th>글</th>
      <td>이수지</td>
    </tr>
    <tr>
      <th>그림</th>
      <td>이수지</td>
    </tr>
    <tr>
      <th>가격</th>
      <td>27,000원</td>
    </tr>
  </table>
  
</body>
</html>

<!DOCTYPE html>
<html lang="ko">
<head>
  <title>테이블 연습3</title>
</head>
<body>
  <h1>테이블 연습 3</h1>
  <table border="1">
    <caption>백종원의 '불고기 샌드위치' 레시피</caption>
    <tr>
      <th colspan="2">레시피</th>
    </tr>

    <tr>
      <th rowspan="2"><img src="./images/img02.jpg" alt="조리방법1"></th>
      <th>조리 방법 1</th>
    </tr>
    <tr>
      <td>식빵에 상추를 원하는 만큼 푸짐하게 덮어주세유</td>
    </tr>

    <tr>
      <th rowspan="2"><img src="./images/img03.jpg" alt="조리방법2"></th>
      <th>조리 방법 2</th>
    </tr>
    <tr>
      <td>마요네즈를 듬뿍 올려유</td>
    </tr>

    <tr>
      <th rowspan="2"><img src="./images/img04.jpg" alt="조리방법3"></th>
      <th>조리 방법 3</th>
    </tr>
    <tr>
      <td>그 위로 불고기를 싸악 올리구</td>
    </tr>

    <tr>
      <th rowspan="2"><img src="./images/img05.jpg" alt="조리방법4"></th>
      <th>조리 방법 4</th>
    </tr>
    <tr>
      <td>다시 식빵으로 덮으면 끝!</td>
    </tr>
  </table>
  
</body>
</html>
