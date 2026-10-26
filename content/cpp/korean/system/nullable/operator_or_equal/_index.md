---
title: operator|=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 오른쪽 인수로 사용하여 현재 객체가 나타내는 값에 operator|=()를 적용합니다.
type: docs
weight: 261
url: /ko/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) 메서드

Applies [operator|=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | SFINAE가 작동하도록 하는 템플릿 매개변수입니다. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | **bool** | [operator|=()](./)이 현재 객체가 나타내는 값에 적용될 때 오른쪽 값으로 사용되는 불리언 값입니다. |

### 반환 값

자기 자신에 대한 참조입니다.

## 참고

* 클래스 [Nullable](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)