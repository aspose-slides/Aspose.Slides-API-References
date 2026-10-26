---
title: operator&=()
second_title: Aspose.Slides C++ API 참조
description: 현재 객체가 나타내는 값에 지정된 값을 오른쪽 인수로 사용하여 operator&=()를 적용합니다.
type: docs
weight: 274
url: /ko/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) 메서드

Applies [operator&=()](./) to the value represented by the current object using the specified value as a right-side argument.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | SFINAE가 작동하도록 하는 템플릿 매개변수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | **bool** | 현재 객체가 나타내는 값에 적용되는 [operator&=()](./)의 오른쪽 값으로 사용되는 부울 값. |

### 반환 값

A reference to the self.

## 관련 항목

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)