# 7/25 웹개발자 양성과정

## HTML(Hyper Text Markup Language)

### HTML

웹 페이지의 구조를 정의하는 언어이다.

<head>- 문서 제목(<title>), 문자 인코딩(<meta charset=”UTF-8”>) 등의 메타데이터와 문서 정보 입력한다.
<body>-웹 페이지의 실제 내용을 작성합니다. 텍스트, 이미지, 링크, 리스트, 테이블 등을 추가한다.
주석-<!-- -->

## CSS(Cascading Style Sheets)

### CSS

웹 페이지의 스타일과 레이아웃을 정의하는 언어이다.
HTML 페이지에 스타일을 지정하는 스타일시트를 작성할 때 사용하는 언어이다.
현대 웹 페이지에서 매우 중요한 역할 수행한다.

### html 요소에 스타일 적용 방법 종류

인라인 스타일시트-태그에 스타일 적용
익스터널 스타일시트-외부에 선언된 스타일 적용
인터널 스타일시트-내부에 스타일을 선언

## Javascript

### Javascript

웹 페이지에 동적 기능을 추가하는 언어이다.

## git과 github

### git 다운로드하기

[Git (git-scm.com)](https://git-scm.com/)에서 다운로드 할 수 있다.

### github에 push하기

vscode에 재접속 후 github에 push하기 위해 터미널(Ctrl + ‘ 또는 Cmd + ‘)에 다음과 같이 입력한다.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git init
git add .
git commit -m "Initial commit"
git remote add origin “https://github.com/yourusername/your-repository.git”
git push -u origin master
```