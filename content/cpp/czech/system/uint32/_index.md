---
title: UInt32
second_title: Aspose.Slides pro C++ - dokumentace API
description: Obsahuje metody pro práci s neoznačeným 32-bitovým celým číslem.
type: docs
weight: 1977
url: /cs/system/uint32/
---
## UInt32 struct

Obsahuje metody pro práci s neoznačeným 32-bitovým celým číslem.

```cpp
class UInt32
```

## Methods

| Method | Description |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neoznačené celé číslo. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neoznačené celé číslo pomocí poskytnutých informací o formátování. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neoznačené celé číslo pomocí poskytnutých informací o formátování a stylu čísla. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neoznačené celé číslo. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 32-bitové neoznačené celé číslo pomocí poskytnutých informací o formátování a stylu čísla. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)