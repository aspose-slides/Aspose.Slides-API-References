---
title: operator<=()
second_title: Aspose.Slides C++ API 레퍼런스
description: 항상 false를 반환합니다.
type: docs
weight: 196
url: /ko/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const 메서드

항상 false를 반환합니다.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const 메서드

현재 개체가 나타내는 값이 지정된 값보다 작거나 같은지, 이러한 값에 [operator<=()](./)를 적용하여 결정합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교 대상 값의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교할 값에 대한 상수 참조 |

### 반환값

현재 객체가 나타내는 값이 지정된 값보다 작거나 같으면 True, 그렇지 않으면 - false

## Nullable::operator<=(const Nullable\<T1\>\&) const 메서드

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값보다 작거나 같은지, 이러한 값에 [operator<=()](./)를 적용하여 결정합니다.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교 대상 [Nullable](../) 객체의 기본 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 비교할 [Nullable](../) 객체에 대한 상수 참조 |

### 반환값

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값보다 작거나 같으면 True, 그렇지 않으면 - false

## 참조

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)