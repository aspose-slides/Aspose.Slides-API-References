---
title: operator=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체에 null을 할당합니다.
type: docs
weight: 14
url: /ko/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) 메서드


현재 객체에 null을 할당합니다.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### 반환값

[Nullable](../) 객체는 null 값을 나타냅니다.

## Nullable::operator=(const T1\&) 메서드


지정된 값으로 객체가 현재 나타내는 값을 교체합니다.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| The | 현재 객체가 나타낼 새 값의 형식 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T1\& | 현재 객체가 나타낼 새 값 |

### 반환값

현재 객체에 대한 참조

## Nullable::operator=(const Nullable\<T1\>\&) 메서드


지정된 값으로 객체가 현재 나타내는 값을 교체합니다.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| The | 현재 객체가 나타낼 새 값의 형식 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | 현재 객체가 나타낼 새 값 |

### 반환값

현재 객체에 대한 참조

## 관련 항목

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)