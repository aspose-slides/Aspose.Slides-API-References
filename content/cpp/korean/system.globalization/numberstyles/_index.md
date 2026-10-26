---
title: NumberStyles
second_title: Aspose.Slides for C++ API 레퍼런스
description: 구문 분석 시 허용되는 숫자 형식입니다.
type: docs
weight: 495
url: /ko/system.globalization/numberstyles/
---
## NumberStyles 열거형

구문 분석 시 허용되는 숫자 형식입니다.

```cpp
enum class NumberStyles : int32_t
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | 숫자가 아닌 기호를 허용하지 않습니다. |
| AllowLeadingWhite | 1 | 선행 공백을 허용합니다. |
| AllowTrailingWhite | 2 | 후행 공백을 허용합니다. |
| AllowLeadingSign | 4 | 선행 부호를 허용합니다. |
| Integer | n/a | 기본 정수 형식입니다. |
| AllowTrailingSign | 8 | 후행 부호를 허용합니다. |
| AllowParentheses | 16 | 음수 값에 괄호를 허용합니다. |
| AllowDecimalPoint | 32 | 소수점을 허용합니다. |
| AllowThousands | 64 | 그룹 구분자를 허용합니다. |
| Number | n/a | 기본 복합 숫자 형식입니다. |
| AllowExponent | 128 | 지수 부호를 허용합니다. |
| Float | n/a | 기본 부동 소수점 숫자 형식입니다. |
| AllowCurrencySymbol | 256 | 통화 기호를 허용합니다. |
| Currency | n/a | 기본 통화 형식입니다. |
| Any | n/a | 모든 형식 지정자를 허용합니다. |
| AllowHexSpecifier | 512 | 16진수 숫자를 허용합니다. |
| HexNumber | n/a | 기본 16진수 형식입니다. |

## See Also

* 네임스페이스 [System::Globalization](../)
* 라이브러리 [Aspose.Slides](../../)