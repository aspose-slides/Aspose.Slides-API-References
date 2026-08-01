---
title: UInt64
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met de unsigned 64-bit integer.
type: docs
weight: 1990
url: /nl/system/uint64/
---
## UInt64 struct

Bevat methoden om te werken met de unsigned 64-bit integer.

```cpp
class UInt64
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit unsigned integer. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit unsigned integer met behulp van de opgegeven opmaakinformatie. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit unsigned integer met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint64_t**\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit unsigned integer. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint64_t**\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit unsigned integer met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint64_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint64_t**\&) |  |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Grootst mogelijke waarde. |
| static constexpr [MinValue](./minvalue/) | Kleinste mogelijke waarde. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)