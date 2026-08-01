---
title: Double
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met het double-precision floating-point getal.
type: docs
weight: 1574
url: /nl/system/double/
---
## Double struct

Bevat methoden om te werken met het double-precision floating-point getal.

```cpp
class Double
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar de equivalente double-precision floating-point waarde. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar de equivalente double-precision floating-point waarde met behulp van de opgegeven opmaakinformatie. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar de equivalente double-precision floating-point waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar de equivalente double-precision floating-point waarde. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar de equivalente double-precision floating-point waarde met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

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

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)