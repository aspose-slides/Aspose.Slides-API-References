---
title: GetTextElementEnumerator()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열의 문자를 반복하기 위한 열거자를 생성합니다.
type: docs
weight: 118
url: /ko/system.globalization/stringinfo/gettextelementenumerator/
---
## StringInfo::GetTextElementEnumerator(const String\&) 메서드

문자열의 문자를 반복하기 위한 열거자를 생성합니다.

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/)를 반복합니다. |

### 반환값

새로 생성된 열거자.

## StringInfo::GetTextElementEnumerator(const String\&, int) 메서드

지정된 인덱스에서 시작하여 문자열의 문자를 반복하기 위한 열거자를 생성합니다.

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str, int index)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/)를 반복합니다. |
| index | int | 시작 인덱스. |

### 반환값

새로 생성된 열거자.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextElementEnumerator](../../textelementenumerator/)
* Class [String](../../../system/string/)
* Class [StringInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)