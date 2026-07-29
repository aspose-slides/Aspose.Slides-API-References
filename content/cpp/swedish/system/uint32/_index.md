---
title: UInt32
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att arbeta med det osignerade 32-bit-heltal.
type: docs
weight: 1977
url: /sv/system/uint32/
---
## UInt32 struktur

Innehåller metoder för att arbeta med det osignerade 32-bit-heltal.

```cpp
class UInt32
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Omvandlar den angivna strängen som innehåller talets strängrepresentation till motsvarande 32-bit-osignerat heltal. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Omvandlar den angivna strängen som innehåller talets strängrepresentation till motsvarande 32-bit-osignerat heltal med den angivna formateringsinformationen. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Omvandlar den angivna strängen som innehåller talets strängrepresentation till motsvarande 32-bit-osignerat heltal med den angivna formateringsinformationen och talstil. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Omvandlar den angivna strängen som innehåller talets strängrepresentation till motsvarande 32-bit-osignerat heltal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Omvandlar den angivna strängen som innehåller talets strängrepresentation till motsvarande 32-bit-osignerat heltal med den angivna formateringsinformationen och talstil. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)