---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Zet de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat om in het overeenkomstige 64-bit unsigned integer.
type: docs
weight: 14
url: /nl/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) method

Zet de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat om in het overeenkomstige 64-bit unsigned integer.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| result | **uint64_t**\& | De referentie naar een 64-bit unsigned integer-variabele waarin het resultaat van de conversie wordt geplaatst. |

### Returnwaarde

True als de conversie geslaagd is, anders - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) method

Zet de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat om in het overeenkomstige 64-bit unsigned integer met behulp van de opgegeven opmaak- en cijfers-stijlinformatie.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een verwijzing naar een object dat de tekenreeks-opmaakinformatie bevat. |
| result | **uint64_t**\& | De referentie naar een 64-bit unsigned integer-variabele waarin het resultaat van de conversie wordt geplaatst. |

### Returnwaarde

True als de conversie geslaagd is, anders - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)