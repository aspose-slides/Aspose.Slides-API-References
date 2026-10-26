---
title: UInt16
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje metody pro práci s neznamenajícím 16-bitovým celým číslem.
type: docs
weight: 1964
url: /cs/system/uint16/
---
## UInt16 struct

Obsahuje metody pro práci s neznamenajícím 16bitovým celým číslem.

```cpp
class UInt16
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové neznamenající celé číslo. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové neznamenající celé číslo pomocí poskytnutých informací o formátování. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové neznamenající celé číslo pomocí poskytnutých informací o formátování a číselném stylu. |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint16_t**\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové neznamenající celé číslo. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint16_t**\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16-bitové neznamenající celé číslo pomocí poskytnutých informací o formátování a číselném stylu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint16_t**\&) |  |
## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |
## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)