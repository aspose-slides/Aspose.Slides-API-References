---
title: SByte
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met het 8-bit geheel getal.
type: docs
weight: 1873
url: /nl/system/sbyte/
---
## SByte struct

Bevat methoden om te werken met de 8-bit geheel getal.

```cpp
class SByte
```

## Methods

| Method | Description |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 8-bit ondertekende geheel getal. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 8-bit ondertekende geheel getal met behulp van de opgegeven opmaakinformatie. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 8-bit ondertekende geheel getal met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 8-bit ondertekende geheel getal. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 8-bit ondertekende geheel getal met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Fields

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Grootst mogelijke waarde. |
| static constexpr [MinValue](./minvalue/) | Kleinste mogelijke waarde. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)