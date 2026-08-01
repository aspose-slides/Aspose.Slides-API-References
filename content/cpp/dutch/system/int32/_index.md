---
title: Int32
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden om te werken met het 32-bit geheel getal.
type: docs
weight: 1041
url: /nl/system/int32/
---
## Int32 klasse

Bevat methoden om te werken met het 32-bit geheel getal.

```cpp
class Int32
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 32-bit ondertekende integer. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 32-bit ondertekende integer met behulp van de opgegeven opmaakinformatie. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 32-bit ondertekende integer met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 32-bit ondertekende integer. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 32-bit ondertekende integer met behulp van de opgegeven opmaakinformatie en getalstijl. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Grootst mogelijke waarde. |
| static constexpr [MinValue](./minvalue/) | Kleinste mogelijke waarde. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)