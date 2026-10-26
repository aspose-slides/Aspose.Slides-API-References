---
title: operator+()
second_title: Aspose.Slides for C++ API 참조
description: Nullable<T> 클래스의 기본 생성된 인스턴스를 반환합니다.
type: docs
weight: 209
url: /ko/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const 메서드

Nullable<T> 클래스의 기본 생성된 인스턴스를 반환합니다.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const 메서드

nullable 및 non-nullable 값을 합산합니다.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 오른쪽 피연산자 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 추가할 값. |

### 반환값

합산 결과.

## Nullable::operator+(const Nullable\<T1\>\&) const 메서드

nullable 값을 합산합니다.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 오른쪽 피연산자 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 추가할 값. |

### 반환값

합산 결과.

## 참조

* 클래스 [Nullable](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)