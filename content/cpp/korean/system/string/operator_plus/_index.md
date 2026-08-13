---
title: operator+()
second_title: Aspose.Slides C++용 API 참조
description: 문자열 연결 연산자.
type: docs
weight: 274
url: /ko/system/string/operator_plus/
---
## String::operator+(const String\&) const 메서드


[String](../) 연결 연산자.

```cpp
String System::String::operator+(const String &str) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 현재 문자열 끝에 추가합니다. |

### 반환값

연결된 문자열.

## String::operator+(const T\&) const 메서드


[String](../) 문자열 리터럴 또는 문자 문자열 포인터와의 연결.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 문자열 리터럴 또는 문자 문자열 포인터 형태 중 하나. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg | const T\& | 현재 문자열과 연결할 엔터티. |

### 반환값

연결된 문자열.

## String::operator+(char_t) const 메서드


```cpp
String System::String::operator+(char_t x) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | char_t | 추가할 문자. |

### 반환값

[String](../) 연결 결과.

## String::operator+(int) const 메서드


```cpp
String System::String::operator+(int i) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | int | 문자열로 변환하여 추가할 정수값. |

### 반환값

[String](../) 연결 결과.

## String::operator+(uint32_t) const 메서드


```cpp
String System::String::operator+(uint32_t i) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | **uint32_t** | 문자열로 변환하여 추가할 값. |

### 반환값

[String](../) 연결 결과.

## String::operator+(double) const 메서드


```cpp
String System::String::operator+(double d) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| d | **double** | 문자열로 변환하여 추가할 값. |

### 반환값

[String](../) 연결 결과.

## String::operator+(int64_t) const 메서드


```cpp
String System::String::operator+(int64_t v) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| v | **int64_t** | 문자열로 변환하여 추가할 값. |

### 반환값

[String](../) 연결 결과.

## String::operator+(const T\&) const 메서드


```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 포인터 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) [ToString()](../tostring/) 호출을 사용하여 문자열로 변환하고 현재 문자열에 추가합니다. |

### 반환값

[String](../) 연결 결과.

## String::operator+(const T\&) const 메서드


```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [ToString()](../tostring/) 를 호출하기 위한 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) [ToString()](../tostring/) 호출을 사용하여 문자열로 변환하고 현재 문자열에 추가합니다. |

### 반환값

[String](../) 연결 결과.

## String::operator+(T) const 메서드


```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 문자열과 연결할 값 유형. bool이어야 함 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) 값을 문자열로 변환하고 추가합니다. |

### 반환값

[String](../) 연결 결과.

## 참조

* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)