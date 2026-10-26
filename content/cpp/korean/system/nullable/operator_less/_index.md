---
title: operator<()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 항상 false를 반환합니다.
type: docs
weight: 170
url: /ko/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const 메서드

항상 false를 반환합니다.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const 메서드

현재 객체가 나타내는 값이 지정된 값보다 작아지는지 여부를 [operator<()](./)를 적용하여 판단합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교 대상 값의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교 대상 값에 대한 상수 참조 |

### 반환 값

현재 객체가 나타내는 값이 지정된 값보다 작으면 true, 그렇지 않으면 false

## Nullable::operator<(const Nullable\<T1\>\&) const 메서드

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값보다 작아지는지 여부를 [operator<()](./)를 적용하여 판단합니다.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교 대상 [Nullable](../) 객체의 기본 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 비교 대상 [Nullable](../) 객체에 대한 상수 참조 |

### 반환 값

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값보다 작으면 true, 그렇지 않으면 false

## 참고

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)