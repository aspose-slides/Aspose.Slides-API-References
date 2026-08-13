---
title: Coalesce()
second_title: Aspose.Slides for C++ API 참조
description: null이 아닌 타입에 대한 '??' 연산자 변환 구현.
type: docs
weight: 170
url: /ko/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) 메서드

null이 아닌 타입에 대한 '??' 연산자 변환 구현.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T0 | LHS 값 유형. |
| T1 | RHS 식을 캡슐화하는 람다 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T0 | LHS 값. |
| func | T1 | RHS 식. |

### 반환값

LHS 값이 null이 아니면 LHS를 반환하고, 그렇지 않으면 RHS 식을 계산하여 결과를 반환합니다.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) 메서드

nullable 타입에 대한 '??' 연산자 변환 구현.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T0 | LHS 값 유형. |
| T1 | RHS 식을 캡슐화하는 람다 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS 값. |
| func | T1 | RHS 식. |

### 반환값

LHS 값이 null이 아니면 LHS를 반환하고, 그렇지 않으면 RHS 식을 계산하여 결과를 반환합니다.

## 참고

* 클래스 [ObjectExt](../)
* 클래스 [Nullable](../../nullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)