---
title: CoalesceInternal()
second_title: C++용 Aspose.Slides API 참조
description: 비null 가능 타입에 대한 '??' 연산자 구현. RT2가 RT1로 변환 가능한 경우에 대한 오버로드.
type: docs
weight: 157
url: /ko/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) 메서드

Implementation of '??' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T0 | LHS 값 유형. |
| T1 | RHS 식을 캡슐화하는 람다의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | RT1 | LHS 값. |
| func | F | RHS 식. |

### 반환 값

LHS 값이 null이 아니면 LHS를 반환하고, 그렇지 않으면 RHS 식을 계산하여 결과를 반환합니다.

## 참조

* 클래스 [ObjectExt](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)