---
title: IsDefined()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값이 열거형 E의 멤버인지 확인합니다.
type: docs
weight: 27
url: /ko/system/enum/isdefined/
---
## Enum::IsDefined(E) 메서드

지정된 값이 열거형 **E**의 멤버인지 확인합니다.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | E | 확인할 값 |

### 반환값

**value**가 열거형 **E**의 멤버이면 True, 그렇지 않으면 false

## Enum::IsDefined(T) 메서드

지정된 값이 열거형 **T**의 멤버인지 확인합니다.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 확인할 값 |

### 반환값

**value**가 열거형 **T**의 멤버이면 True, 그렇지 않으면 false

## Enum::IsDefined(const String\&) 메서드

지정된 이름을 가진 값이 열거형 **E**의 멤버에 포함되는지 확인합니다.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 확인할 이름 |

### 반환값

지정된 이름을 가진 **E** 열거형 멤버가 존재하면 True

## 참고

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)