---
title: NullableBoolHelper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: this와 other가 둘 다 null이 아니면 확인하고 람다를 호출하는 헬퍼 함수입니다. 구현에 사용됩니다.
type: docs
weight: 105
url: /ko/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const 메서드

두 객체 **this**와 **other**가 모두 null이 아니면 람다를 호출하는 헬퍼 함수입니다. 구현에 사용됩니다.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 다른 nullable 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | const T1\& | 비교할 다른 nullable 값. |
| f | const std::function\<**bool**()>\& | **this**와 **other**가 모두 null이 아닐 때 호출할 람다. |
| default_if_both_are_null | **bool** | 두 값이 모두 null인 경우 반환 값. |

### 반환 값

둘 중 하나가 null이면 false; 두 값이 모두 null이면 **default_if_both_are_null**; 두 값이 모두 null이 아니면 **f** 호출 결과.

## 관련 항목

* 클래스 [Nullable](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)