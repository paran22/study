## 49장 Babel과 Webpack을 이용한 ES6+/ES.NEST 개발 환경 구축
- 크롬, 사파리, 파이어폭스, 엣지 같은 에버그린 브라우저evergreen browser의 ES6 지원율은 약 98%로 거의 대부분 ES6 사양을 지원한다.
- 하지만 매년 새롭게 도입되는 ES6+ 버전과 제안 단계에 있는 ES 제안 사양(ES.NEXT)은 브라우저에 따라 지원 여부가 다르다.
### 49.1 Babel
- 최신 사양의 소스코드를 구형 브라우저에서도 동작할 수 있게 소스코드로 변환하는 것을 트랜스파일링이라고 하고, 이를 위해 Babel과 같은 트랜스파일러를 사용한다.
- Babel의 플러그인을 모아둔 Babel 프리셋을 사용하면 필요한 플러그인들을 프로젝트 지원 환경에 맞춰 동적으로 결정해준다.
- 설치가 필요한 Babel의 플러그인은 Babel 홈페이지에서 검색할 수 있다.

### 49.2 Webpack
- Webpack은 의존 관계에 있는 자바스크립트, CSS, 이미지 등의 리소스를 하나(또는 여러 개)의 파일로 번들링하는 모듈 번들러이다.
- Webpack을 사용하면 별도의 모듈 로더가 필요 없다. 또, 여러 개의 자바스크립트 파일을 하나로 번들링하므로 HTML 파일에서 script 태그로 여러 개의 자바스크립트 파일을 로드하지 않아도 된다.
- Webpack이 모듈을 번들링할 때 Babel을 사용하여 트랜스파일링되도록 설정할 수 있다.
