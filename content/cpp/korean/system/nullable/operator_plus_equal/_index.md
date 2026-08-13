---
title: operator+=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체를 재설정하여 null 값으로 나타내도록 합니다.
type: docs
weight: 235
url: /ko/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) 메서드

현재 객체를 재설정하여 null 값으로 나타내도록 합니다.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### 반환 값

self의 복사본

## Nullable::operator+=(const T1\&) 메서드

현재 객체가 나타내는 값에 [operator+=()](./)을 적용하고, 지정된 값을 오른쪽 인수로 사용합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [operator+=()](./)의 오른쪽 값으로 사용되는 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 현재 객체가 나타내는 값에 적용되는 [operator+=()](./)의 오른쪽 값으로 사용되는 값에 대한 상수 레퍼런스. |

### 반환 값

self에 대한 레퍼런스

## Nullable::operator+=(const Nullable\<T1\>\&) 메서드

지정된 [Nullable](../) 객체가 나타내는 값을 오른쪽 인수로 사용하여 현재 객체가 나타내는 값에 [operator+=()](./)을 적용합니다.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [operator+=()](./)의 오른쪽 인수로 사용되는 값을 나타내는 [Nullable](../) 객체의 기본 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 현재 객체가 나타내는 값에 적용되는 [operator+=()](./)의 오른쪽 인수로 사용되는 값을 나타내는 [Nullable](../) 객체에 대한 상수 레퍼런스. |

### 반환 값

self에 대한 레퍼런스

## 관련 항목

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)