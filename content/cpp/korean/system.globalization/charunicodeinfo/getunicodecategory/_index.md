---
title: GetUnicodeCategory()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자의 Unicode 범주를 가져옵니다.
type: docs
weight: 40
url: /ko/system.globalization/charunicodeinfo/getunicodecategory/
---
## CharUnicodeInfo::GetUnicodeCategory(char16_t) 메서드

문자의 Unicode 범주를 가져옵니다.

```cpp
static UnicodeCategory System::Globalization::CharUnicodeInfo::GetUnicodeCategory(char16_t ch)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ch | char16_t | Unicode 문자. |

### 반환값

Unicode 범주.

## CharUnicodeInfo::GetUnicodeCategory(const String\&, int) 메서드

문자열에서 지정된 인덱스에 있는 문자의 Unicode 범주를 가져옵니다.

```cpp
static UnicodeCategory System::Globalization::CharUnicodeInfo::GetUnicodeCategory(const String &str, int index)
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Unicode 문자를 포함하는 문자열. |
| index | int | Unicode 문자의 인덱스. |

### 반환값

Unicode 범주.

## 참조

* 열거형 [UnicodeCategory](../../unicodecategory/)
* 클래스 [CharUnicodeInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)