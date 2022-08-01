# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

가나다라 마바사 아자차카 타파하 1
가나다라 마바사 아자차카 타파하 2

# 줄바꿈(Line Breaks)

가나다라 마바사 아자차카 타파하 1 <br/>
가나다라 마바사 아자차카 타파하 2 <br/>
가나다라 마바사 아자차카 타파하 3 <br/>
가나다라 마바사 아자차카 타파하 4 <br/>

# 강조(Emphasis)

_이탤릭_ <br/>
**두껍게** <br/>
**_이탤릭 + 두껍게_** <br/>
_**두껍게 + 이탤릭**_ <br/>
~~취소선~~ <br/>
<u>밑줄</u> <br/>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 슌서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

*target 속성은 마크다운에서 지원하지 않는다. <br/>
<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)
*링크와 이미지의 차이 <br/>

<!-- [HEROPY](https://heropy.blog/css/images/logo.png) -->
<!-- ![HEROPY](https://heropy.blog/css/images/logo.png) -->

*이미지에 링크 설정하기 <br/>

<!-- [![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/) -->

# 인용문(BlockQuote)
*기존 <br/>
남의 말이나 글에서 직접 또는 간접으로 따온 문장. <br/>
(네이버 국어 사전)

*변경(인용문일 경우)
>남의 말이나 글에서 직접 또는 간접으로 따온 문장. <br/>
>(네이버 국어 사전)

*인용문 중첩
>인용문을 작성하세요!
>>중첩된 인용문
>>> 중첩된 인용문 1 <br/>
>>> 중첩된 인용문 2 <br/>
>>> 중첩된 인용문 3

# 인라인(inline) 코드 강조
*원본 <br/>
CSS에서 background 혹은 background-image 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

*변경(인라인 강조) <br/>
CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

*HTML 블록 코드에 하이라이팅이 반영됨
```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

*CSS 블록 코드에 하이라이팅이 반영됨
```css
.list > li {
  position: absolute;
  top: 40px;
}
```

*Javascript 블록 코드에 하이라이팅이 반영됨
```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

*터미널에 입력하는 bash 명령어에도 하이라이팅이 반영됨
```bash
$ git commit -m 'Study Markdown'
```

*개발언어 아닌 텍스트도 블록코드로 강조 가능
```plaintext
가나다라 마바사
아자차카 타파하
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|--|--
static | 기준없음 | O
relative | 요소자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X


*기본값은 왼쪽정렬이다.

*가운데 정렬 예시 ('의미' 열 부분)

값 | 의미 | 기본값
--|:--:|--
static | 기준없음 | O
relative | 요소자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X


*오른쪽 정렬 예시('기본값' 열 부분)

값 | 의미 | 기본값
--|--|--:
static | 기준없음 | O
relative | 요소자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X

# 원시 HTML(RAW HTML)

동해물과 <u>백두산</u>이 마르고
닳도록 <br/>
하느님이 보우하사 우리나라 만세

*u 태그 대신에 span 에 underline 속성을 넣어도 같은 결과 : <br />
동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고
닳도록 <br/>
하느님이 보우하사 우리나라 만세

*아래 내용은 (마크다운 문법이 지원이 안되므로) width 속성을 직접 원시 HTML로 입력 : <br/>
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>


# 수평선(Horizontal Rule)

*수평선이 되는 기호들 (세번씩 넣기)
---
***
___
