---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API 레퍼런스
description: '??=' 연산자 번역 구현.
type: docs
weight: 183
url: /ko/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) 메서드

‘??=’ 연산자 번역 구현.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T0 | LHS 값 유형. |
| T1 | RHS 표현식을 캡슐화하는 람다 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T0\& | LHS 값. |
| func | T1 | RHS 표현식. |

### 반환 값

LHS 값이 null이 아니면 LHS를 반환하고, 그렇지 않으면 RHS 표현식을 계산하여 결과를 반환합니다.

## 참고

* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)