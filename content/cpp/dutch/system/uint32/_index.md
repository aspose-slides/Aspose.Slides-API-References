---
title: UInt32
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met het ongetekende 32-bit geheel getal.
type: docs
weight: 1977
url: /nl/system/uint32/
---
## UInt32 struct

Bevat methoden om te werken met het ongetekende 32-bit geheel getal.

```cpp
class UInt32
```

## Methods

| Methode | Beschrijving |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende geheel getal. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende geheel getal met de opgegeven opmaakinformatie. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende geheel getal met de opgegeven opmaakinformatie en getalstijl. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende geheel getal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende geheel getal met de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Fields

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Grootste mogelijke waarde. |
| static constexpr [MinValue](./minvalue/) | Kleinste mogelijke waarde. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)