---
title: Nullable()
second_title: Aspose.Slides for C++ API 레퍼런스
description: null값을 나타내는 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system/nullable/nullable/
---
## Nullable::Nullable() 생성자

null값을 나타내는 인스턴스를 생성합니다.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) 생성자

null을 나타내는 인스턴스를 생성합니다.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) 생성자

지정된 값을 기본 형식 T의 값으로 변환(필요한 경우)하여 나타내는 [Nullable](../) 클래스의 인스턴스를 생성합니다.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 지정된 값의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const T1\& | 새로 생성된 [Nullable](../) 객체가 나타낼 값을 가리키는 상수 참조 |

## Nullable::Nullable(const Nullable\<T1\>\&) 생성자

지정된 [Nullable](../) 객체가 나타내는 값을 나타내는 인스턴스를 생성합니다. 지정된 nullable 객체는 생성된 인스턴스의 기본 형식과 다른 형식의 값을 가질 수 있으며, 이 경우 해당 값은 형식 T로 변환됩니다.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 지정된 [Nullable](../) 객체가 나타내는 값의 형식 |

## 참고

* 클래스 [Nullable](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)