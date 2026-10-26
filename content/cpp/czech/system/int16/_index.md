---
title: Int16
second_title: Aspose.Slides pro C++ – dokumentace API
description: Obsahuje metody pro práci s 16-bitovým celým číslem.
type: docs
weight: 1028
url: /cs/system/int16/
---
## Int16 třída

Obsahuje metody pro práci s 16bitovým celým číslem.

```cpp
class Int16
```

## Methods

| Metoda | Popis |
| --- | --- |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16bitové podepsané celé číslo. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16bitové podepsané celé číslo s použitím poskytnutých informací o formátování. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16bitové podepsané celé číslo s použitím poskytnutých informací o formátování a číselného stylu. |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int16_t**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16bitové podepsané celé číslo. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int16_t**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní 16bitové podepsané celé číslo s použitím poskytnutých informací o formátování a číselného stylu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int16_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int16_t**\&) |  |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)