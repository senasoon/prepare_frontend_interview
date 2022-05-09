# prepare_frontend_interview

<b>프론트엔드 기술 면접을 위한 핸드북 만들기</b>

면접의 인터뷰어 분들이 JS의 수 많은 개념들을 순서대로 질문을 하지는 않습니다.

하지만 자바스크립트의 연관되어 있는 개념들을 순서대로 나열하고 핸드북 형식으로 보다 보면,

모르는 개념을 파악하고 한눈에 보는 것에 있어서 도움이 되지 않을까 싶어 제작하게 되었습니다.

크게 ① CS ② HTML/CSS ③ JavaScript 로 나누었습니다

① CS인 computer science에는 자바스크립트 이외에 지식들에 대한 조금 잡다한 내용이 담길 예정입니다

목차를 보고 해당 내용이 마음에 드실 경우에 보시는 것을 추천합니다!

## 질문의 빈도

```
① JS > ② CS > ③ React > ④ HTML/CSS
```

## contribute

① 클론 받기 / 포크 받기

```
$ git clone https://github.com/junh0328/prepare_frontend_interview.git
```

② 내용 추가 또는 변경하기

```
ex)

- [타입과 인터페이스 🔥](#타입과-인터페이스) >>> [xxx](#xxx) 마크다운 구조

  - 타입스크립트를 왜 쓰나요? (본인이 느낀점)
  - 타입과 인터페이스의 차이를 아나요?
  - 제네릭이란?
```

③ 목차에도 해당 내용 추가하기

```
ex)

- `타입과 인터페이스 🔥` >>> 백틱 내부에 제목 그대로 표시 `xxx`

  - 타입스크립트를 왜 쓰나요? (본인이 느낀점)
  - 타입과 인터페이스의 차이를 아나요?
  - 프로젝트 진행 시에 어떤 상황에서 타입을 쓰고 어떤 상황에서 인터페이스를 썼나요?
```

④ 이슈 생성 및 PR 날리기

예시 이슈: (https://github.com/junh0328/prepare_frontend_interview/issues/6)

```
템플릿을 작성해 두었으니, 해당 예시 이슈에 맞춰 작성해주시면 됩니다!
```

## <a href="./cs.md">① Computer Science</a>

- `프로세스와 스레드 🔥`

  - 프로세스가 뭔가요?
  - 스레드가 뭔가요?
  - 프로세스와 스레드는 어떤 차이가 있나요?

- `싱글 스레드와 멀티 스레드 🔥`

  - 싱글 스레드 장점
  - 싱글 스레드 단점
  - 멀티 스레드 장점
  - 멀티 스레드 단점

- `HTTP 🔥`

  - HTTP란 뭔가요?
  - HTTP 프로토콜의 가장 큰 특징은 뭔가요?
  - URL은 뭔가요?
  - HTTP/1.1 과 HTTP/2.0의 차이는 뭔가요?
  - HTTPS는 HTTP랑 뭐가 다른가요?
  - 심화) 공개키 (비대칭키) 방식이 뭔가요?

- `쿠키 세션 🔥`

  - 쿠키, 세션을 왜 쓰나요? 🔥🔥
  - 쿠키가 뭔가요? 🔥🔥
  - 세션이 뭔가요? 🔥🔥
  - 쿠키와 세션의 차이는 어떤 점이 있을까요? 🔥🔥

- `CORS 🔥`

  - CORS가 뭔가요?
  - CORS를 겪고 직접 해결해 본 경험이 있으면 말해주세요

- `SaaS 🔥`

  - SaaS가 뭔가요?
  - 기타 비즈니스 유형​은 뭐가 있나요?

- `개발 방법론 🔥`

  - 폭포수 방법론이란 뭔가요?
  - 애자일 방법론이란 뭔가요?

- `Cache 🔥`

- 캐시란 무엇인가요?

- `CI CD 🔥`

  - CI CD란 뭔가요?

- `CDN 🔥`

  - CDN이란 뭔가요?

- `테스트 🔥`

  - 테스트란 무엇인가요?
  - 테스트의 예는 어떤 것들이 있나요?
  - 테스트는 왜 해야 하나요?
  - 유닛 테스트란 무엇인가요?
  - 통합 테스트란 무엇인가요?
  - E2E 테스트란 무엇인가요?

- `웹팩 🔥`

  - 웹팩이란?
  - 모듈이란?
  - 모듈 번들링이란?
  - 웹팩이 등장한 이유 웹팩 사용 시에 이점
  - 바벨이란?
  - 웹팩의 주요 속성 4가지

- `타입과 인터페이스 🔥🔥🔥`

  - 이 글을 보시는 분들께
  - 타입스크립트를 왜 쓰나요? (본인이 느낀점)
  - 타입과 인터페이스의 차이를 아나요?
  - 프로젝트 진행 시에 어떤 상황에서 타입을 쓰고 어떤 상황에서 인터페이스를 썼나요?

## <a href="./html_css.md">② HTML/ CSS</a>

### **HTML**

- `DOCTYPE 🔥`

  - DOCTYPE에 대하여 설명하시오
  - meta 태그에 대해서 알고 있나요?
  - meta 태그의 요소에 대해서 아는대로 말해보세요

- `웹 표준 및 웹 접근성 🔥`

  - 웹 표준이란?
  - HTML5에서 추가된 내용이 있나요?
  - 웹 접근성이란?
  - 웹 접근성에 맞는 마크업 예시 몇가지 말해보시오
  - 시멘틱 태그란 무엇인가 왜 사용하는가
  - 텍스트 관련 태그
  - SEO란 무엇인가?
  - Button 태그의 Default type은 무엇인가?
  - Section 태그와 article 태그의 차이점

- `그 외 🔥`

  - 이미지 크기가 클 경우 렌더링 속도가 느려질텐데 이를 개선하기 위한 방법
  - UI란 무엇인지 설명하시오

- `SVG란 ? 🔥`

  - SVG 장점과 단점
  - SVG 내부 도형에 대해 아는게 있나요?

<br />

### **CSS**

- `display 🔥`

  - block
  - inline
  - inline-block
  - none

- `position에 대하여 설명해보세요. 🔥`

  - static
  - relative
  - fixed
  - absolute

- `float가 어떻게 작동하는가 🔥`

- `Flexbox나 Grid 스펙을 사용해본 적이 있나요 ? 🔥`

  - flex 를 사용하는 이유가 무엇인가요?
  - Grid를 사용하는 이유가 무엇인가요?

- `이미지 태그를 스타일로 대체하는 법 🔥`
- `반응형 웹의 3요소 🔥🔥`
- `CSS selector가 어떠한 원리로 동작하나요? 🔥`
- `반응형웹과 적응형웹에 설명하시오 🔥`

  - 반응형 웹이란? 🔥
  - 적응형 웹이란?

- `PX, EM에 대해 설명하시오 🔥🔥`

  - 절대단위
  - 상대단위
  - px
  - em
  - ex
  - %
  - pt

- `CSS 적용 우선순위 🔥🔥`
- `CSS-in-JS에 대해서 설명해 주세요. 🔥`
- `CSS 전처리기(CSS preprocessors)를 사용해보셨나요? 🔥`

  - 사용해봤다면 장점과 단점

- `padding과 margin의 차이가 무엇인가요? 🔥`

  - padding에 대하여
  - margin에 대하여

## <a href="./js.md">③ JavaScript</a>

- `프로그래밍 🔥`

  - 프로그래밍이란 뭐라고 생각하나요?
  - 컴파일러는 뭐고 인터프리터는 뭔가요?

- `자바스크립트란 🔥`

  - 자바스크립트의 특징은 뭐가 있나요?

- `변수 🔥`

  - 변수란 무엇인가요?
  - 식별자란 무엇인가요? 🔥
  - 변수를 선언한다는 것은 어떤 것을 의미하나요?
  - var 키워드는 뭔가요?
  - 호이스팅이 뭔가요? 🔥🔥🔥🔥
  - var 키워드의 문제점은 무엇이 있나요? 🔥🔥
  - let 키워드는 var 키워드와 어떤 점이 다른가요? 🔥🔥🔥
  - TDZ 🔥🔥🔥
  - const 키워드는 어떤 특징이 있나요? 🔥🔥
  - 식별자 네이밍 규칙은 어떤 것들이 있나요?
  - 네이밍 컨벤션은 어떤 것들이 있나요?
  - 리터럴이 뭔가요?

- `데이터 타입 🔥`

  - 데이터 타입의 종류는 어떤 것들이 있나요? 🔥
  - 심벌 타입은 뭐죠?
  - 데이터 타입은 왜 필요할까요? 🔥
  - 정적 타이핑이 뭔가요?
  - 동적 타이핑이 뭔가요?

- `타입변환과 단축 평가 🔥`

  - 명시적 타입 변환이 뭔가요?
  - 명시적 타입 변환 함수를 예를 들어볼 수 있나요?
  - 암묵적 타입 변환이 뭔가요?
  - truthy / falsy 한 값이 뭔가요?

- `배열 🔥`

  - 자바스크립트의 배열은 자료구조의 배열과 같나요?
  - 배열의 메서드는 어떤 종류가 있나요?
  - 고차 함수에 대해서 아나요?
  - forEach 메서드와 map메서드의 차이점에 대해 알고 있나요?

- `객체 리터럴 🔥`

  - 자바스크립트에서 객체란 뭘까요?
  - 함수와 메서드의 차이점에 대해 알고 계신가요?
  - 자바스크립트에서 객체를 생성하는 방법은 어떤 것들이 있나요?

- `원시 값과 객체 비교 🔥`

  - 동적 타이핑을 지원하는 자바스크립트에서 데이터의 타입을 크게 2개로 나누는 이유가 있을까요?
  - 값에 의한 전달이 뭔가요?
  - 참조에 의한 전달이 뭔가요?

- `함수 🔥`

  - 자바스크립트에서 함수를 정의하는 방법은 몇가지가 있나요?
  - 함수 선언문과 함수 표현식은 어떤 차이가 있나요?
  - 즉시 실행 함수(IIFE)에 대해 알고 있나요? 알고 있다면 아는 내용에 대해 말해보세요

- `스코프 🔥`

  - 스코프가 뭔가요? 🔥🔥🔥
  - 스코프에는 어떤 종류가 있죠? 🔥🔥
  - 렉시컬 스코프를 아나요? 안다면 렉시컬 스코프는 무엇을 의미하나요? 🔥
  - 전역 변수로 변수를 선언하면 생기는 문제점은 무엇이 있을까요?

- `생성자 함수에 의한 객체 생성 🔥`

  - 생성자 함수가 뭔가요?
  - 객체 리터럴로 만들 때와는 무슨 차이가 있죠? 왜 생성자 함수를 사용하나요?
  - 생성자 함수가 객체(인스턴스)를 생성하는 과정에 대해 간략하게 설명해줄 수 있나요?

- `함수와 일급 객체 🔥`

  - 일급 객체가 뭔가요?
  - 자바스크립트에서 함수가 일급 객체라면, 일급 객체로 뭘 할 수 있나요?
  - 꼬리 질문) 함수형 프로그래밍이 뭔가요? 🔥🔥
  - 꼬리 질문) 순수 함수가 뭔가요? 일반 함수와는 어떤 차이가 있죠? 🔥🔥

- `프로토타입 🔥`

  - 객체지향 프로그래밍은 무엇을 의미하나요? 🔥
  - 객체지향 프로그래밍의 특징에 대해 말해볼 수 있나요? 🔥
  - 자바스크립트는 객체지향 프로그래밍 언어인가요?
  - 프로토타입이 뭔가요?

- `strict mode 🔥`

  - strict mode가 뭔가요?
  - strict mode를 통해 무엇을 예방할 수 있죠?

- `빌트인 객체 🔥`

  - 빌트인 객체가 뭔가요? 종류는 어떤게 있죠?
  - 래퍼 객체에 대해서 알고 있나요?

- `this 🔥`

  - this가 뭔가요? 🔥
  - this 바인딩이란? 🔥
  - this는 동적으로 바인딩이 된다고 하는데 바인딩되는 객체가 어떻게 다르나요?

- `실행 컨텍스트 🔥`

  - 실행 컨텍스트에 대해 말해보세요 🔥🔥

- `클로저 🔥`

  - 클로저에 대해서 아나요? 🔥🔥🔥
  - 클로저를 사용하면 뭐가 좋죠? 🔥🔥
  - 클로저를 어떻게 생성하나요? 🔥

- `클래스 🔥`

  - 자바스크립트에서 클래스가 생기기 전에는 어떤 방식으로 객체지향 패턴을 구현했나요?
  - 그럼 생성자 함수와 클래스는 어떤 차이가 있나요?
  - 클래스 정의
  - 클래스의 상속

- `스프레드 문법 🔥`

  - spread 문법이 뭔가요?
  - 어떤 상황에서 사용할 수 있죠?

- `구조 분해 할당 🔥`

  - 구조 분해 할당이 뭔가요?
  - 구조 분해 할당은 크게 어떤 종류가 있나요?

- `브라우저 렌더링 과정 🔥`

  - 브라우저의 렌더링 과정에 대해 설명해보세요 🔥
  - 브라우저의 렌더링 과정에 자바스크립트는 어떻게 동작하나요? 🔥
  - `<script></script>` 태그를 `<body></body>` 태그 밑에 둬야하는 이유가 있을까요?

- `DOM 🔥`

  - DOM이 뭔가요?
  - DOM을 구성하는 건 뭐가 있나요?

- `이벤트 🔥`

  - 마우스 이벤트 타입에는 뭐가 있나요? click 말고 클릭을 대체할 수 있는 이벤트가 있나요?
  - 그 외에 알고 있는 대표적인 이벤트가 있나요?
  - 이벤트 핸들러를 등록하는 방식에는 어떤 것들이 있나요?
  - 이벤트 전파(propagation)에 대해서 알고 있나요?
  - 이벤트 위임(delegation)에 대해서 알고있나요? 🔥
  - e.preventDefault 에 대해 알고 있나요?
  - e.stopPropagation

- `타이머 🔥`

  - 호출 스케쥴링이 무엇인가요?
  - 타이머 함수에는 어떤 것들이 있나요?
  - 이벤트가 과도하게 호출되어 성능에 문제를 일으킬 경우에 할 수 있는 어떤 일을 통해 해결할 수 있나요?
  - 디바운스에 대해서 알고 있나요?
  - 쓰로틀에 대해서 알고 있나요?

- `비동기 프로그래밍 🔥`

  - 동기와 비동기의 차이점에 대해서 설명해줄 수 있나요? 🔥🔥

    - 한줄 요약

  - 이벤트 루프와 태스크 큐에 대해서 알고 있나요? 🔥🔥🔥
  - 마이크로태스크 큐에 대해서 알고 있나요? 🔥🔥
  - 태스크 큐와 마이크로태스크 큐 중 어떤 것이 먼저 실행되나요? 🔥🔥

- `Ajax 🔥`

  - Ajax가 뭔가요 어떤 것을 담당하고 있죠?
  - Ajax를 사용하면 기존 방식과 어떤 차이가 있을까요?
  - JSON 이 뭔가요?
  - JSON이 제공하는 정적 프로토타입 메서드에 대해 몇가지 말해볼 수 있나요?
  - Ajax로 HTTP 요청을 보내기 위해서는 어떤 방법을 사용할 수 있나요?
  - XMLHttpRequest와 fetch 메서드의 차이는 무엇이라고 생각하시나요? 🔥

- `REST API 🔥`

  - REST API가 뭔가요?
  - REST API의 구성은 어떤 것이 있나요?
  - REST API를 설계하는데 중요한 것이 있을까요?
  - HTTP 요청 메서드에 대해서 아는대로 얘기해보세요
  - HTTP 상태 코드를 아는대로 말해주세요 🔥

- `Promise 🔥`

  - 콜백이란 뭐라고 생각하나요? 🔥
  - 프로미스가 뭔가요? 🔥
  - 프로미스 생성 방법
  - 프로미스의 상태를 나타내는 것은 어떤 것들이 있나요? 🔥
  - 프로미스 빌트인 객체가 제공하는 정적 메서드에 대해 알고 있나요? 🔥

- `제너레이터와 async await 🔥`

  - 제너레이터란 뭔가요? 일반 함수와는 어떤 차이가 있죠?
  - 제너레이터의 구조
  - async/await 가 뭔가요? 기존의 Promise와는 어떤 차이가 있죠? 🔥
  - Promise와 async/await의 차이점 한 줄 요약 🔥

- `에러 🔥`

  - 에러처리를 왜 해야 하나요? 🔥
  - 자바스크립트에서 에러를 처리하는 방법에는 뭐가 있을까요?

- `모듈 🔥`

  - 모듈이 뭔가요?

## <a href="./react.md">④ React</a>

- `React 시작🔥`
- `리액트는 라이브러리인가요 프레임워크 인가요?🔥`
- `리액트를 사용하는 이유🔥🔥`
- `virtual DOM에 대해서 아나요?🔥🔥`
- `React에서 함수 컴포넌트와 클래스 컴포넌트의 차이 🔥`
- `리액트에서 함수형 컴포넌트라고 부르지 않고 함수 컴포넌트라고 부르는 이유가 무엇인가요 🔥`
- `props와 state의 차이🔥`
- `Props가 컴포넌트간에 전달받는 것이라고 했는데 자식에서 부모로도 전달할 수 있는가 🔥`
- `FLUX에 대해서 아나요? 🔥🔥`
- `리덕스에 대해서 아나요? 🔥🔥`
- `리덕스의 기본 원칙은? 🔥🔥`
- `React에서 state의 불변성을 유지하라는 말이 있는데 이에 대해 설명해달라 🔥`
- `리듀서 내부에서 불변성을 지키는 이유는? 전개 연산자의 단점을 해결할 수 있는 방법은 무엇인가 🔥`
- `리액트 사용시에 부수효과로 인해 생기는 문제점이 있다면 🔥🔥`

  - 부수 효과를 일으키는 함수 (불순 함수)
  - 부수 효과를 일으키지 않는 함수 (순수 함수)
  - 요약

- `컴포넌트의 라이프 사이클 메서드 🔥🔥`

  - 이해
  - 메서드 종류 🔥

- `Hooks의 종류 🔥🔥`

  - useState
  - useEffect
  - useReducer
  - useMemo
  - useCallback
  - useRef
  - 커스텀 Hooks

- `useMemo와 useCallback의 차이를 아나요 🔥🔥`

- `리액트에서 setState는 비동기 동작인가요 동기 동작인가요? 🔥`
- `setState가 비동기 동작을 취했을 때 얻을 수 있는 이점은 무엇인가요? 🔥`
- `useLayoutEffect는 무엇인가요? 🔥`
- `리액트의 성능개선 방법에 대해서 설명해주세요`

- `컴포넌트에서 이벤트를 실행시키기 위해서는 어떻게 핸들링해야 하나요?🔥`
- `SPA가 뭔가요?🔥`

  - SPA의 단점

- `SSR이 뭔가요?🔥`
- `SEO가 뭔가요?🔥`

  - TTV, TTI

- `하이드레이션에 대해 알고 있나요 🔥`
- `Next의 렌더링 수행 방식 🔥`
- `Next를 쓴 이유가 있나요 ? 🔥`
- `Next를 구성하는 기본 설정 파일에 대해서 알고 있나요? 🔥`
- `사전 렌더링을 위해 사용해 본 함수가 있나요 🔥`

## <a href="./data_structure.md">⑤ 자료구조</a>

- `자료구조란 무엇인가요 🔥`

  - 효율적으로 데이터를 관리해야 하는 이유 (예)

- `대표적인 자료구조는 어떤 것들이 있나요 🔥`

  - 선형 구조
  - 비 선형 구조

- `리스트 🔥`
- `큐 🔥`
- `스택 🔥`
- `링크드 리스트 🔥`
- `해쉬 테이블 🔥`
- `트리 🔥`
- `힙 🔥`
- `그래프 🔥`

## <a href="./about_me.md">⑥ '피면접자'가 생각하는 예상 질문 리스트</a>

## <a href="./question_list.md">⑦ 비밀스러운 면접 후기 및 질문 리스트</a>

## 레퍼런스

- [프론트 엔드 개발자 면접 질문 정리 🔥](https://sunnykim91.tistory.com/121)
- [Interview_Question_for_Beginner 🔥](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)
