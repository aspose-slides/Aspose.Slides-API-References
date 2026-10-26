---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 값이 지정된 Nullable 객체가 나타내는 값과 같은지 확인합니다.
type: docs
weight: 131
url: /ko/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const 메서드

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값과 같은지 확인합니다.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | [Nullable](../) 객체와 비교할 기본 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교할 [Nullable](../) 객체에 대한 상수 레퍼런스 |

### 반환 값

현재 객체가 나타내는 값이 지정된 [Nullable](../) 객체가 나타내는 값과 같은 경우 true, 그렇지 않으면 false

## 참고

* 클래스 [Nullable](../)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)