---
title: operator!=()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 값이 null이 아닌지 확인합니다.
type: docs
weight: 144
url: /ko/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const 메서드


현재 객체가 나타내는 값이 null이 아닌지 확인합니다.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### 반환값

현재 객체가 나타내는 값이 null이 아니면 true, 그렇지 않으면 false

## Nullable::operator!=(const T1\&) const 메서드


현재 객체가 나타내는 값이 지정된 값과 같지 않은지 확인합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교할 값의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교할 값에 대한 const 참조 |

### 반환값

현재 객체가 나타내는 값이 지정된 값과 같지 않으면 true, 그렇지 않으면 false

## Nullable::operator!=(const Nullable\<T1\>\&) const 메서드


현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값과 같지 않은지 확인합니다.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [Nullable](../) 객체와 비교할 기본 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 비교할 [Nullable](../) 객체에 대한 const 참조 |

### 반환값

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값과 같지 않으면 true, 그렇지 않으면 false

## 관련 항목

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)