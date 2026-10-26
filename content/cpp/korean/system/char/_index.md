---
title: Char
second_title: Aspose.Slides for C++ API 레퍼런스
description: UTF-16 코드 유닛으로 표현된 문자를 조작하기 위한 메서드를 제공합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 170
url: /ko/system/char/
---
## Char 클래스

UTF-16 코드 유닛으로 표시되는 문자를 조작하기 위한 메서드를 제공합니다. 이것은 인스턴스 서비스를 제공하지 않는 정적 타입입니다. 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class Char
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | UTF-32 코드 유닛을 [System::String](../string/) 클래스의 인스턴스로 변환합니다. |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | 지정된 UTF-16 서러게이트 쌍을 UTF-32 코드 유닛으로 변환합니다. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | 문자열의 지정된 위치에 있는 UTF-16 인코딩 문자 또는 서러게이트 쌍의 값을 UTF-32 코드 유닛으로 변환합니다. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | 지정된 UTF-16 문자를 배정밀도 부동소수점 숫자값으로 변환합니다. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | 지정된 문자의 유니코드 범주를 나타내는 값을 반환합니다. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | 지정된 문자가 ASCII 공백 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 유니코드 제어 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsControl](./iscontrol/)(char_t) | 지정된 문자가 유니코드 제어 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 10진 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | 지정된 문자열의 지정된 인덱스에 있는 문자가 10진 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsDigit](./isdigit/)(char_t) | 지정된 문자가 10진 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | 지정된 문자열의 지정된 인덱스에 있는 문자가 UTF-16 높은 서러게이트 코드 유닛인지 여부를 판단합니다. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 높은 서러게이트인지 여부를 판단합니다. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | 지정된 문자가 높은 서러게이트인지 여부를 판단합니다. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 유니코드 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLetter](./isletter/)(char_t) | 지정된 문자가 유니코드 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 유니코드 문자 또는 10진 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | 지정된 문자가 유니코드 문자 또는 10진 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 소문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLower](./islower/)(char_t) | 지정된 문자가 소문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | 지정된 문자열의 지정된 인덱스에 있는 문자가 소문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 낮은 서러게이트인지 여부를 판단합니다. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | 지정된 문자가 낮은 서러게이트인지 여부를 판단합니다. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsNumber](./isnumber/)(char_t) | 지정된 문자가 숫자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 구두점 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | 지정된 문자가 구두점 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 구분 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | 지정된 문자가 구분 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | 지정된 문자가 UTF-16 서러게이트 코드 유닛인지 여부를 판단합니다. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | 지정된 문자열의 지정된 인덱스에 있는 문자가 UTF-16 서러게이트 코드 유닛인지 여부를 판단합니다. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | 지정된 두 문자가 UTF-16 서러게이트 쌍인지 여부를 판단합니다. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | 지정된 문자 버퍼에서 연속된 두 문자가 서러게이트 쌍인지 여부를 판단합니다. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 기호 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | 지정된 문자가 기호 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | 지정된 문자열의 지정된 인덱스에 있는 문자가 대문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 대문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsUpper](./isupper/)(char_t) | 지정된 문자가 대문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 공백 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | 지정된 문자가 공백 문자로 분류되는지 여부를 판단합니다. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | 지정된 문자열의 지정된 인덱스에 있는 문자가 공백 문자로 분류되는지 여부를 판단합니다. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다. |
| static char_t [ToLower](./tolower/)(char_t) | 지정된 문자를 소문자로 변환합니다. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 문자를 소문자로 변환합니다. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | 지정된 문자를 소문자로 변환합니다. |
| static char_t [ToUpper](./toupper/)(char_t) | 지정된 문자를 대문자로 변환합니다. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 문자를 대문자로 변환합니다. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | 지정된 문자를 대문자로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | 단일 문자로 이루어진 문자열을 UTF-16 문자로 변환하려 시도합니다. 입력 문자열이 null이 아니며 길이가 정확히 한 문자일 때만 함수가 성공합니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)