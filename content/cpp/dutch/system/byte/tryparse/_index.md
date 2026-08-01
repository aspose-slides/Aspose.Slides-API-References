---
title: TryParse()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit unsigned integer.
type: docs
weight: 14
url: /nl/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit unsigned integer.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd. |
| result | **uint8_t**\& | De referentie naar een 8-bit unsigned integer-variabele waarin het resultaat van de conversie wordt geplaatst. |

### Returnwaarde

True als de conversie geslaagd is, anders - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bit unsigned integer met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |
| result | **uint8_t**\& | De referentie naar een 8-bit unsigned integer-variabele waarin het resultaat van de conversie wordt geplaatst. |

### Returnwaarde

True als de conversie geslaagd is, anders - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) methode




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Byte](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)