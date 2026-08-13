---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자와 연관된 숫자 값을 가져옵니다.
type: docs
weight: 27
url: /ko/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) 메서드

지정된 문자와 연관된 숫자 값을 가져옵니다.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char16_t | 유니코드 문자. |

### 반환값

지정된 문자가 숫자 문자가 아닌 경우 숫자 값 또는 -1을 반환합니다.

## CharUnicodeInfo::GetNumericValue(const String\&, int) 메서드

문자열의 지정된 인덱스에 있는 문자와 연관된 숫자 값을 가져옵니다.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 유니코드 문자를 포함하는 문자열. |
| index | int | 유니코드 문자의 인덱스. |

### 반환값

지정된 문자가 숫자 문자가 아닌 경우 숫자 값 또는 -1을 반환합니다.

## 참조

* 클래스 [CharUnicodeInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)