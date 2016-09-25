

**Front-End School Week1**
=========================


###1. Web Accessibility & Web Standards

- Web Accessibility
- Web Standards

----------


####**Web Accessibility**

>The power of the Web is in its universality, access by everyone regardless of disability is an essential aspect.
>
>**Tim Berners - Lee**

장애에 대한 이해

* 시각 장애 - 전맹, 저시력
* 청각 장애
* 지체 장애 - 절단 및 지체기능 장애 
* 뇌병변 장애


환경에 대한 이해 다양한 Platform

* Cross Browsing
* SEO(Search Engine Optimization) [^1]
* 저사양 또는 저속회선

-----


####**Web Standards**
1. HTML5: 건강한 신체
2. CSS3: 근사한 스타일링
3. JavaScript: 스마트한 두뇌

>웹 표준: [World Wide Web Consortiums](https://www.w3.org)

----

**웹 접근성 보장 및 개선을 위한 두가지 방법론**

- 가이드라인 준수

> - 4가지 원칙
> **P** erceivable(인지, 자각)
> **O** perable(운용)
> **U** nderstandable(이해)
> **R** obust(탄탄한, 견고한)
> 
> - [참고 - 웹 표준의 이해](http://webdir.tistory.com/34)
> - [WCAG 2.0](https://www.w3.org/WAI/): Web Content Accessibility Guidelines

- 웹 표준 준수
 
> - HTML5 
> - CSS3 
> - JavaScript


[^1]: 검색 엔진 최적화. 검색 엔진에서 특정 키워드로 검색 되었을때, 자신의 포스트가 상위에 노출되게 하는 것.

----

###2. HTML5

-----

- **컨텐츠 모델(Contents Model)**
 명확한 정보구조 설계 및 구성을 위해 카테고리를 정의하여 각 요소별로 비슷한 성격을 가지고 있는 것끼리 그룹화 한 것.
 - 카테고리
   Sectioning Root, Metadata Content, Flow Content, Sectioning Content, Heading Content, Phrasing Content, Embedded Content, Interactive Content, Palpable Content, Script-supporting Elements, Transparent Content

 - Sectioning Content
   ``` 
   <article></article>
   <aside></aside>
   <nav></nav>
   <section></section>
   ```
- **아웃라인 알고리즘(Outline Algorithm)**
 정보 구조를 명확히 할 수 있도록 하기 위함.
 웹 페이지의 정보 구조를 판별할 수 있는 개념(책의 목차).
 
 ```
 <!-- heading content -->
 <h1></h1>
 <h2></h2>
 
  <!-- sectioning content -->
 <section></section>
 <article></article>

 <!-- sectioning root -->
 <blockquote></blockquote>
 <body></body>
 ```


- **API**

- **Markup**
 - tag, element, content
 
```
<!-- tag -->
<p>

<!-- element -->
<p>Heoyunjee</p>

<!-- atrribute -->
<input type="text" id="user" required> <!-- required: 논리속성 -->
```

- **Doctype**
모든 웹 브라우저에서 표준 모드(Standards Mode)로 렌더링될 수 있도록 하는 역할
```
<!DOCTYPE html>
```

- **Encoding**
```
<meta charset="utf-8">
```

- **Semantic Markup**
컴퓨터가 웹 정보자원의 의미를 이해할 수 있도록 문서의 논리적인 구조를 묘사하는 것
>장점
– 접근성이 좋아짐
– SEO(Search Engine Optimization)
– 수정이 용이해짐
– 코드 가독성이 좋아짐
– 코드와 데이터의 재사용성이 높아짐

```
<!-- 섹션의 주제 -->
<header>
``` 

```
<!-- 다른 페이지나 현재 페이지의 특성 부분 -->
<nav>
```

```
<!-- 문서나 애플리케이션의 섹션 -->
<!-- 컨텐츠를 연관된 내용으로 묶은 형태로, 소제목과 함께 표시 -->
<section>
```

```
<!-- 문서, 페이지, 사이트 등에서 하나의 독립된 요소 -->
<!-- 따로 떼어내어 사용할 수 있는 내용 -->
<article>
```

```
<!-- 현재 문서의 컨텐츠와 큰 관련이 없는 부분 -->
<aside>
```

```
<!-- 24시간제(YYYY-MM-DD/ HH:MM:SS) -->
<!-- 2013-05-06T14:00:00+09:00 -->
<!-- T문자로 구분하고 문자열 끝에 타임존 정보를 더하면 된다. -->
<time>
```

```
<!-- 참조용으로 문서 내 이동 -->
<mark>
```

```
<!-- 그림, 사진, 일러스트 등의 컨텐트에 연관된 캡션을 표시 -->
<figure>
```

```
<!-- 통상 작성자, 관련문서에 대한 링크, 저작권 표시 등 섹션에 대한 정보 -->
<footer>
```

----

###3. CSS3

