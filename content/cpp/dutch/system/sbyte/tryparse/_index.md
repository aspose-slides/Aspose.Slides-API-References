---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar de equivalente ondertekende 8-bit integer.
type: docs
weight: 14
url: /nl/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) method


Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar de equivalente ondertekende 8-bit integer.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| result | **int8_t**\& | De referentie naar een 8-bit ondertekende integervariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie slaagt, anders - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) method


Converteert de opgegeven string die de stringrepresentatie van een getal bevat naar de equivalente ondertekende 8-bit integer met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de stringrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat. |
| result | **int8_t**\& | De referentie naar een 8-bit ondertekende integervariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie slaagt, anders - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)