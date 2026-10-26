---
title: operator==()
second_title: Aspose.Slides for C++ API 참조
description: 동등 비교 연산자.
type: docs
weight: 300
url: /ko/system/string/operator_equal_equal/
---
## String::operator==(const String\&) const 메서드

동등 비교 연산자.

```cpp
bool System::String::operator==(const String &str) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 현재 문자열과 비교하기 위해. |

### 반환 값

두 문자열이 모두 null이거나 두 문자열이 모두 null이 아니고 일치하면 true, 그렇지 않으면 false.

## String::operator==(std::nullptr_t) const 메서드

문자열이 null인지 확인합니다. [IsNull()](../isnull/) 호출과 동일한 논리를 적용합니다.

```cpp
bool System::String::operator==(std::nullptr_t) const
```

### 반환 값

문자열이 null이면 true, 그렇지 않으면 false.

## 참고

* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)