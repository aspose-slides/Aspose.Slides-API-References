---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 16-bit ondertekende gehele getal.
type: docs
weight: 14
url: /nl/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) methode


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 16-bit ondertekende gehele getal.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De tekenreeks om te converteren. |
| result | **int16_t**\& | De referentie naar een 16-bit ondertekende gehele variabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie geslaagd is, anders - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) methode


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige 16-bit ondertekende gehele getal met behulp van de meegegeven opmaakinformatie en nummerstijl.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De tekenreeks om te converteren. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |
| result | **int16_t**\& | De referentie naar een 16-bit ondertekende gehele variabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie geslaagd is, anders - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) methode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) methode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) methode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int16](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)