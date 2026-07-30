---
title: Int64
second_title: Aspose.Slides pro C++ referenční příručku API
description: Obsahuje metody pro práci s 64bitovým celým číslem.
type: docs
weight: 1054
url: /cs/system/int64/
---
## Int64 třída


Obsahuje metody pro práci s 64bitovým celým číslem.

```cpp
class Int64
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec obsahující číselnou reprezentaci na odpovídající 64bitové podepsané celé číslo. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující číselnou reprezentaci na odpovídající 64bitové podepsané celé číslo pomocí poskytnutých informací o formátování. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí zadaný řetězec obsahující číselnou reprezentaci na odpovídající 64bitové podepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla. |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int64_t**\&) | Převádí zadaný řetězec obsahující číselnou reprezentaci na odpovídající 64bitové podepsané celé číslo. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int64_t**\&) | Převádí zadaný řetězec obsahující číselnou reprezentaci na odpovídající 64bitové podepsané celé číslo pomocí poskytnutých informací o formátování a stylu čísla. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int64_t**\&) |  |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)