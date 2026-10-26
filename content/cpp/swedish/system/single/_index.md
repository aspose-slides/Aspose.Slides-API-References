---
title: Single
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att arbeta med enkelprecisions-flyttal.
type: docs
weight: 1899
url: /sv/system/single/
---
## Enkel struct

Innehåller metoder för att arbeta med enkelprecisionsflyttal.

```cpp
class Single
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller en sifferrepresentation till motsvarande enkelprecisions-flyttal. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller en sifferrepresentation till motsvarande enkelprecisions-flyttal med den angivna formateringsinformationen. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller en sifferrepresentation till motsvarande enkelprecisions-flyttal med den angivna formateringsinformationen och talstil. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Konverterar den angivna strängen som innehåller en sifferrepresentation till motsvarande enkelprecisions-flyttal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Konverterar den angivna strängen som innehåller en sifferrepresentation till motsvarande enkelprecisions-flyttal med den angivna formateringsinformationen och talstil. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Minsta positiva värde som är större än noll. |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |
| static constexpr [NaN](./nan/) | Värde som inte är ett tal. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negativ oändlighet. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positiv oändlighet. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)