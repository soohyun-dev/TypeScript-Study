## 타입스크립트 Union Type

### Union Type

- 타입스크립트에서 굉장히 많이 쓰인다. 잘 익혀두자.
- OR 역할 가지고 있다.
- type으로 정한 값들 중에서만 사용할 수 있다.

```TypeScript
type Walk = "go" | "stop" | "back";
function move(walk: Walk) {
    console.log(walk);
}

move("go");  // go
move("jump"); // 매개변수 할당 불가 error

```
