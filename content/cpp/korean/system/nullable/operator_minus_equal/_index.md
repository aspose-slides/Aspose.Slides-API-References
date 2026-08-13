---
title: operator-=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: null 값을 나타내는 Nullable 클래스의 인스턴스를 반환합니다.
type: docs
weight: 248
url: /ko/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) 메서드

[Nullable](../) 클래스의 인스턴스를 반환하며, 이는 null 값을 나타냅니다.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) 메서드

[operator-=()](./)를 현재 객체가 나타내는 값에 적용하며, 지정된 값을 오른쪽 인수로 사용합니다.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [operator-=()](./)의 오른쪽 값으로 사용되는 값의 타입 |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| other | const T1\& | 현재 객체가 나타내는 값에 적용되는 [operator-=()](./)의 오른쪽 값으로 사용되는 값에 대한 상수 참조입니다. |

### 반환 값

현재 객체에 대한 참조

## Nullable::operator-=(const Nullable\<T1\>\&) 메서드

[operator-=()](./)를 현재 객체가 나타내는 값에 적용하며, 지정된 [Nullable](../) 객체가 나타내는 값을 오른쪽 인수로 사용합니다.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [Nullable](../) 객체의 기본 타입으로, 해당 객체가 나타내는 값은 [operator-=()](./)의 오른쪽 인수로 사용됩니다. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 현재 객체가 나타내는 값에 적용되는 [operator-=()](./)의 오른쪽 인수로 사용되는 [Nullable](../) 객체에 대한 상수 참조입니다. |

### 반환 값

현재 객체에 대한 참조

## 참고

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)