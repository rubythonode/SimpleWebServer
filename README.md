# SimpleWebServer
긴급히 웹 서버가 필요할 때 유-용!

파일 하나, 65줄짜리 node.js 기반 코드입니다.

## 제공하는 기능
* root 경로로 접근 시 index.html 제공
* javascript, css, jpg, png 파일 제공
* 500, 404 오류 화면 제공

## 설정
맨 윗줄의 PORT를 수정해서 쓰시면 됩니다.
```javascript
var PORT = 8413;

...
```

## 실행
```
node SimpleWebServer.js
```

## 라이센스
[MIT](LICENSE)

## 작성자
[Young Jae Sim](https://github.com/Hanul)