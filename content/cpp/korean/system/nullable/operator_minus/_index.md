---
title: operator-()
second_title: Aspose.Slides for C++ API 레퍼런스
description: nullable와 null 포인터 값을 뺍니다.
type: docs
weight: 222
url: /ko/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const 메서드

nullable와 null 포인터 값들을 뺍니다.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 오른쪽 피연산자 유형, nullptr_t이어야 합니다. |

### 반환 값

빈 [Nullable](../) 객체.

## Nullable::operator-(const T1\&) const 메서드

nullable와 null이 아닌 값을 뺍니다.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 오른쪽 피연산자 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 뺄 값. |

### 반환 값

뺄셈 결과.

## Nullable::operator-(const Nullable\<T1\>\&) const 메서드

nullable 값을 뺍니다.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 오른쪽 피연산자 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 뺄 값. |

### 반환 값

뺄셈 결과.

## 참조

* 클래스 [Nullable](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)