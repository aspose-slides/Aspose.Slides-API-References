---
title: TryParse()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende gehele getal.
type: docs
weight: 14
url: /nl/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende gehele getal.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| result | **uint32_t**\& | De referentie naar een 32-bit ongetekende gehele getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie gelukt is, anders - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ongetekende gehele getal met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |
| result | **uint32_t**\& | De referentie naar een 32-bit ongetekende gehele getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie gelukt is, anders - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) methode


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) methode


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) methode


```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)