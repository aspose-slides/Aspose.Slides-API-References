---
title: Single
second_title: Reference API knihovny Aspose.Slides pro C++
description: Obsahuje metody pro práci s číslem s jednoduchou přesností floating-point.
type: docs
weight: 1899
url: /cs/system/single/
---
## Jedna struktura

Obsahuje metody pro práci s číslem s jednoduchou přesností floating-point.

```cpp
class Single
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu single-precision floating-point. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu single-precision floating-point pomocí poskytnutých informací o formátování. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu single-precision floating-point pomocí poskytnutých informací o formátování a stylu čísla. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu single-precision floating-point. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu typu single-precision floating-point pomocí poskytnutých informací o formátování a stylu čísla. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Nejmenší kladná hodnota větší než nula. |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |
| static constexpr [NaN](./nan/) | Hodnota, která není číslo. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negativní nekonečno. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Pozitivní nekonečno. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)