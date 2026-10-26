---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 동등하지 않은 비교 연산자.
type: docs
weight: 313
url: /ko/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const 메서드

동등하지 않은 비교 연산자.

```cpp
bool System::String::operator!=(const String &str) const
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../)를 현재와 비교하기 위해. |

### 반환 값

두 문자열이 모두 null이거나 둘 다 null이 아니면서 일치하면 false, 그 외에는 true.

## String::operator!=(std::nullptr_t) const 메서드

문자열이 null이 아닌지 확인합니다. [IsNull()](../isnull/) 호출과 동일한 논리를 적용합니다.

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### 반환 값

문자열이 null이면 false, 그 외에는 true.

## 관련 항목

* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)