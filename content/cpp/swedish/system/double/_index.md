---
title: Double
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder för att arbeta med dubbelprecisionsflyttal.
type: docs
weight: 1574
url: /sv/system/double/
---
## Double struktur

Innehåller metoder för att arbeta med dubbelprecisionsflyttal.

```cpp
class Double
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecisionsflyttal. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecisionsflyttal med hjälp av den angivna formateringsinformationen. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecisionsflyttal med hjälp av den angivna formateringsinformationen och talstilen. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecisionsflyttal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecisionsflyttal med hjälp av den angivna formateringsinformationen och talstilen. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Minsta positiva värdet som är större än noll. |
| static constexpr [MaxValue](./maxvalue/) | Största möjliga värde. |
| static constexpr [MinValue](./minvalue/) | Minsta möjliga värde. |
| static constexpr [NaN](./nan/) | Värde som inte är ett tal. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negativ oändlighet. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positiv oändlighet. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)