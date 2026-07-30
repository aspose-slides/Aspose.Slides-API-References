---
title: Int32
second_title: Aspose.Slides pro C++ API Reference
description: Obsahuje metody pro práci s 32bitovým celým číslem.
type: docs
weight: 1041
url: /cs/system/int32/
---
## Int32 třída


Obsahuje metody pro práci s 32bitovým celým číslem.

```cpp
class Int32
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 32bitové podepsané celé číslo. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 32bitové podepsané celé číslo pomocí poskytnutých formátovacích informací. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 32bitové podepsané celé číslo pomocí poskytnutých formátovacích informací a číselného stylu. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 32bitové podepsané celé číslo. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | Převede zadaný řetězec obsahující textovou reprezentaci čísla na odpovídající 32bitové podepsané celé číslo pomocí poskytnutých formátovacích informací a číselného stylu. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Největší možná hodnota. |
| static constexpr [MinValue](./minvalue/) | Nejmenší možná hodnota. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)