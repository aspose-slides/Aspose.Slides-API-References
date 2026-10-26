---
title: UInt16
second_title: Aspose.Slides for C++ API 참조
description: 부호 없는 16비트 정수와 작업하기 위한 메서드를 포함합니다.
type: docs
weight: 1964
url: /ko/system/uint16/
---
## UInt16 struct

부호 없는 16비트 정수와 작업하기 위한 메서드를 포함합니다.

```cpp
class UInt16
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information and number style. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit unsigned integer using the provided formatting information and number style. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |

## 필드

| 필드 | 설명 |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 가능한 가장 큰 값. |
| static constexpr [MinValue](./minvalue/) | 가능한 가장 작은 값. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)