---
title: CharUnicodeInfo
second_title: Aspose.Slides for C++ API 참조
description: 유니코드 문자에 대한 정보를 가져옵니다.
type: docs
weight: 14
url: /ko/system.globalization/charunicodeinfo/
---
## CharUnicodeInfo 클래스

유니코드 문자에 대한 정보를 가져옵니다.

```cpp
class CharUnicodeInfo
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static int [GetDecimalDigitValue](./getdecimaldigitvalue/)(char16_t) | 지정된 문자의 십진수 자리값을 가져옵니다. |
| static int [GetDecimalDigitValue](./getdecimaldigitvalue/)(const [String](../../system/string/)\&, int) | 문자열의 지정된 인덱스에 있는 문자의 십진수 자리값을 가져옵니다. |
| static int [GetDigitValue](./getdigitvalue/)(char16_t) | 지정된 문자의 자리값을 가져옵니다. |
| static int [GetDigitValue](./getdigitvalue/)(const [String](../../system/string/)\&, int) | 문자열의 지정된 인덱스에 있는 문자의 자리값을 가져옵니다. |
| static **double** [GetNumericValue](./getnumericvalue/)(char16_t) | 지정된 문자와 연관된 숫자값을 가져옵니다. |
| static **double** [GetNumericValue](./getnumericvalue/)(const [String](../../system/string/)\&, int) | 문자열의 지정된 인덱스에 있는 문자와 연관된 숫자값을 가져옵니다. |
| static [UnicodeCategory](../unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char16_t) | 문자의 유니코드 범주를 가져옵니다. |
| static [UnicodeCategory](../unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(const [String](../../system/string/)\&, int) | 문자열의 지정된 인덱스에 있는 문자의 유니코드 범주를 가져옵니다. |

## 참고

* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)