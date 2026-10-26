---
title: GetDigitValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자에 대한 숫자 값을 반환합니다.
type: docs
weight: 14
url: /ko/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) 메서드

지정된 문자에 대한 숫자 값을 가져옵니다.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char16_t | 유니코드 문자. |

### 반환 값

해당 문자가 숫자가 아니면 -1을 반환합니다.

## CharUnicodeInfo::GetDigitValue(const String\&, int) 메서드

문자열의 지정된 인덱스에 있는 문자의 숫자 값을 가져옵니다.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 유니코드 문자를 포함하는 문자열. |
| index | int | 유니코드 문자의 인덱스. |

### 반환 값

해당 문자가 숫자가 아니면 -1을 반환합니다.

## 참고

* 클래스 [CharUnicodeInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)