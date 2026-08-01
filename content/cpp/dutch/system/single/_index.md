---
title: Single
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met het enkel-precisie floating-point-getal.
type: docs
weight: 1899
url: /nl/system/single/
---
## Enkele struct


Bevat methoden om te werken met het enkel-precisie floating-point-getal.

```cpp
class Single
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige enkel-precisie floating-point-waarde. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige enkel-precisie floating-point-waarde met behulp van de opgegeven opmaakinformatie. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige enkel-precisie floating-point-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige enkel-precisie floating-point-waarde. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige enkel-precisie floating-point-waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Kleinste positieve waarde die groter is dan nul. |
| static constexpr [MaxValue](./maxvalue/) | Grootste mogelijke waarde. |
| static constexpr [MinValue](./minvalue/) | Kleinste mogelijke waarde. |
| static constexpr [NaN](./nan/) | Waarde die geen getal is. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatieve oneindigheid. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positieve oneindigheid. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)