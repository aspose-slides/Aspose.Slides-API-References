---
title: UInt32
second_title: Aspose.Slides for C++ API 레퍼런스
description: 부호 없는 32비트 정수와 작업하기 위한 메서드를 포함합니다.
type: docs
weight: 1977
url: /ko/system/uint32/
---
## UInt32 구조체

부호 없는 32비트 정수와 작업하기 위한 메서드를 포함합니다.

```cpp
class UInt32
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | 지정된 문자열(숫자의 문자열 표현을 포함) 을 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 문자열(숫자의 문자열 표현을 포함) 을 제공된 형식 정보를 사용하여 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함) 을 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | 지정된 문자열(숫자의 문자열 표현을 포함) 을 32비트 부호 없는 정수로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함) 을 32비트 부호 없는 정수로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 가능한 가장 큰 값. |
| static constexpr [MinValue](./minvalue/) | 가능한 가장 작은 값. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)