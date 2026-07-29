---
title: SByte
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att arbeta med 8-bitars heltal.
type: docs
weight: 1873
url: /sv/system/sbyte/
---
## SByte struktur

Innehåller metoder för att arbeta med 8-bitars heltal.

```cpp
class SByte
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Konverterar den specificerade strängen som innehåller talets strängrepresentation till motsvarande 8-bitars signerade heltal. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den specificerade strängen som innehåller talets strängrepresentation till motsvarande 8-bitars signerade heltal med den tillhandahållna formateringsinformationen. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den specificerade strängen som innehåller talets strängrepresentation till motsvarande 8-bitars signerade heltal med den tillhandahållna formateringsinformationen och talstil. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Konverterar den specificerade strängen som innehåller talets strängrepresentation till motsvarande 8-bitars signerade heltal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Konverterar den specificerade strängen som innehåller talets strängrepresentation till motsvarande 8-bitars signerade heltal med den tillhandahållna formateringsinformationen och talstil. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)