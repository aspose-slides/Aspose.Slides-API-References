---
title: Double
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje metody pro práci s číslem s dvojitou přesností s plovoucí desetinnou čárkou.
type: docs
weight: 1574
url: /cs/system/double/
---
## Struktura Double

Obsahuje metody pro práci s číslem s dvojitou přesností s plovoucí desetinnou čárkou.

```cpp
class Double
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností s plovoucí desetinnou čárkou. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností s plovoucí desetinnou čárkou pomocí poskytnutých informací o formátování. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností s plovoucí desetinnou čárkou pomocí poskytnutých informací o formátování a stylu čísla. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností s plovoucí desetinnou čárkou. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Převádí zadaný řetězec obsahující textovou reprezentaci čísla na ekvivalentní hodnotu s dvojitou přesností s plovoucí desetinnou čárkou pomocí poskytnutých informací o formátování a stylu čísla. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Nejmenší kladná hodnota větší než nula. |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |
| static constexpr [NaN](./nan/) | Hodnota, která není číslo. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negativní nekonečno. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Kladné nekonečno. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)