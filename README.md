# Week 1-1

## 함수와 구현의 차이에 대해서

```js
// 1. 함수를 선언
function func() {
  // 2. 함수를 구현
  // some code
}

// 3. 함수를 사용한다.
func();
```

```js
// TypeScript is Javascript with syntax for types.
=> 타입 구문이 있는 JavaScript
```

타입스크립트가 자랑하는 꼭지중에 하나.
vscode TS + JS , electron으로 만듦
호환성? - 자바스크립트
Safety at Scale

- Javascript 를 이해하는 타입 추론을 사용?
- 추가적인 코드 없이도 훌륭한 도구를 제공

Rust???

npm, github, typeScript 마이크로소프트 생태계안에 있음

## TypeScript 효과?

### 나의, 우리의 데이터 기술서

- 객체와 함수의 생김새를 정의
- 데이터를 코드로 설명할 수 있는 데이터 기술서
- 편집기에서 문서 및 버그를 검출할 수 있다.

```ts
interface Person {
  name: string;
  age: number;
  gender: "M" | "F";
}
```

객체 지향? => 코드로 복잡할 내용을 표현할 수 없는 부분을 객체로 풀어서 설명한다는 느낌?

#### interface

```ts
interface Name {

} // 인터페이스는 객체를 생성하려고 하는구나?

type Name =
// 타입은 다 때려넣을 수 있네?
```

마이크로소프트에서 왜 타입스크립트를 내놓게 되어있는지를 생각해보는 것이 중요하다.

```ts
// @ts-check
=> ts 체크 해준다.

function compact(arr: string[]) {

  return arr
}

```

D.ts 구현부가 빠져있는 파일

googling

### 실습 방법

타입을 먼저 선언하는 연습을 할 것
타입 추론
타입스크립트가 어림 짐작한다.
.D.TS 비교해보기

### 1. Void는 ts 문법일까? js 문법일까?
js에도 void는 있다.

Typescript = javaScript + type Syntax

### 2. Void는 js에도 있을까요?

자바스크립트와 타입스크립트 각 문법의 차이점들 유념할 것.

### interface vs type
- interface => 객체를 묘사하고 원형을 설계하는 모델링
- type alias => 인터페이스가 하는 것들을 그럴싸하게 한다..?


---

# Week 1-2 | Interface for TypeScript

- 인터페이스란?
- `객체의 원형` 신경 썼으면 좋겠음
  - typescrit sahpe of object => MDN 참고해보자

# Week 2-1 | Safety Application for TypeScript

- 타입스크립트는 컴파일 단에서 에러를 잡아주는 녀석인데 런타임에서 안전하게 사용하려면 어떻게 해요?
  - Type Guard!!!
  - 런타임에서 안전하게 쓰는 방안에 대해 고민해야한다.
- 런타임 vs 컴파일

# 2-2 |

- 타입스크립트 공존 ?
