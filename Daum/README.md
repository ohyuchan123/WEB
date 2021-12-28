# 공부내용

HTML title 이미지를 변경하는 방법에 대해 알게 되었다
```HTML
<link rel="shortcut icon" type="image/x-icon" href="/Daum/image/title.png">
```

opacity는 요소의 투명도를 설정한다
```css
opacity: .01;
```

cursor 속성은 요소 위에 마우스 커서가 올라갔을 때   
보여줄 모양을 지정합니다
```css
/*키워드 값*/
cursor: pointer;
cursor: auto;

/*URL, 대체 키워드*/
cursor: url(hand.cur),pointer;

/* URL과 좌표 및 대체 키워드
crsor: url(cursor1.png) 4 12, auto;
cursor: url(cursor2.png) 2 2, pointer;

/* 전역 값 */
cursor: inherit;
cursor: initial;
cursor: unset;
```

채크 박스 만드는 법
```html
    <div class="set_login" > 
        <form class="all_agree" action="a.jsp">
            <input type="checkbox" name="gender" value="login_state_maintain">
            <label class="checkbox">로그인 상태 유지</label>
        </form>
    </div>
```

채크 박스 크기 조절
```css
input[type="checkbox"]{
    width: 25px;
    height: 25px;
}
```

(12/28)