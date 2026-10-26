---
title: operator==()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 값이 null인지 확인합니다.
type: docs
weight: 118
url: /ko/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const method

현재 객체가 나타내는 값이 null인지 확인합니다.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### 반환 값

True if the value represented by the current object is null, otherwise - false

## Nullable::operator==(const T1\&) const method

현재 객체가 나타내는 값이 지정된 값과 같은지 확인합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교할 값의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교할 값에 대한 상수 참조 |

### 반환 값

True if the value represented by the current object is equal to the specified value, otherwise - false

## Nullable::operator==(const Nullable\<T1\>\&) const method

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값과 같은지 확인합니다.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [Nullable](../) 객체와 비교하기 위한 기본 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | [Nullable](../) 객체와 비교하기 위한 상수 참조 |

### 반환 값

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## 관련 항목

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)