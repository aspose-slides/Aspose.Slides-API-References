---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스칼라 값에 대한 해시 코드를 반환합니다.
type: docs
weight: 2484
url: /ko/system/gethashcode/
---
## System::GetHashCode(const T\&) 함수


지정된 스칼라 값에 대한 해시 코드를 반환합니다.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 해시 코드를 생성하는 값의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 해시 코드를 생성할 값 |

### 반환값

지정된 값에 대해 생성된 해시 코드

## System::GetHashCode(const T\&) 함수


지정된 객체에 대한 해시 코드를 반환합니다.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 해시 코드를 생성하는 객체의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 해시 코드를 생성할 객체를 가리키는 [SmartPtr](../smartptr/) |

### 반환값

지정된 객체에 대해 생성된 해시 코드

## System::GetHashCode(const T\&) 함수


예외인 지정된 객체에 대한 해시 코드를 반환합니다.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 해시 코드를 생성하는 객체의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 해시 코드를 생성할 객체를 포함하는 Exception Wrapper |

### 반환값

지정된 객체에 대해 생성된 해시 코드

## System::GetHashCode(const T\&) 함수


스마트 포인터도 아니고 예외도 아닌 지정된 객체에 대한 해시 코드를 반환합니다.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 해시 코드를 생성하는 객체의 타입 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 해시 코드를 생성할 객체에 대한 const 참조 |

### 반환값

지정된 객체에 대해 생성된 해시 코드

## System::GetHashCode(const std::thread::id\&) 함수


std::thread::id에 대한 특수화; 지정된 스레드 객체에 대한 해시 코드를 반환합니다.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## 참조

* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)