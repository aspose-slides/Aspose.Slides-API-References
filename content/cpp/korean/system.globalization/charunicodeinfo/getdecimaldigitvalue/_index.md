---
title: GetDecimalDigitValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자에 대한 10진수 숫자 값을 반환합니다.
type: docs
weight: 1
url: /ko/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) 메서드

지정된 문자에 대한 10진수 숫자 값을 가져옵니다.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char16_t | Unicode 문자. |

### 반환 값

지정된 문자가 10진수 숫자가 아니면 -1을 반환하고, 그렇지 않으면 10진수 숫자 값을 반환합니다.

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) 메서드

문자열에서 지정된 인덱스에 있는 문자에 대한 10진수 숫자 값을 가져옵니다.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Unicode 문자를 포함하고 있는 문자열. |
| index | int | Unicode 문자의 인덱스. |

### 반환 값

지정된 문자가 10진수 숫자가 아니면 -1을 반환하고, 그렇지 않으면 10진수 숫자 값을 반환합니다.

## 참고

* 클래스 [CharUnicodeInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)