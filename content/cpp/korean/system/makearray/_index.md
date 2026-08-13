---
title: MakeArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새로운 Array 객체를 생성하고, 지정된 초기화 목록의 요소로 채운 뒤, 해당 Array 객체를 가리키는 스마트 포인터를 반환하는 팩터리 함수입니다.
type: docs
weight: 2029
url: /ko/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) 함수

지정된 초기화 목록의 요소로 [Array](../array/) 객체를 새로 생성하고 채운 뒤, [Array](../array/) 객체를 가리키는 스마트 포인터를 반환하는 팩터리 함수입니다.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 구성하는 [Array](../array/) 객체의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| init | std::initializer_list\<T\> | 배열을 채우는 요소를 포함하는 초기화 목록 |

### 반환 값

구성된 [Array](../array/) 객체를 가리키는 스마트 포인터

## System::MakeArray(Args\&&...) 함수

지정된 인수를 생성자에 전달하여 새로운 [Array](../array/) 객체를 생성하는 팩터리 함수입니다.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 구성하는 [Array](../array/) 객체의 요소 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | Args\&&... | [Array](../array/) 객체의 생성자에 전달되는 인수 |

### 반환 값

구성된 [Array](../array/) 객체를 가리키는 스마트 포인터

## System::MakeArray(Integral, Args\&&...) 함수

지정된 인수를 생성자에 전달하여 새로운 [Array](../array/) 객체를 생성하는 팩터리 함수입니다.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 함수가 구성하는 [Array](../array/) 객체의 요소 유형 |
| Integral | 배열 크기의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| size | Integral | 생성되는 배열의 크기 |
| args | Args\&&... | [Array](../array/) 객체의 생성자에 전달되는 인수 |

### 반환 값

구성된 [Array](../array/) 객체를 가리키는 스마트 포인터

## 참고

* Typedef [ArrayPtr](../arrayptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)