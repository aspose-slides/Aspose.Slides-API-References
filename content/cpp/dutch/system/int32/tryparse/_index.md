---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks met de stringrepresentatie van een getal naar het overeenkomstige 32-bit ondertekende gehele getal.
type: docs
weight: 14
url: /nl/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) methode


Converteert de opgegeven tekenreeks met de stringrepresentatie van een getal naar het overeenkomstige 32-bit ondertekende gehele getal.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De tekenreeks die moet worden geconverteerd. |
| result | **int32_t**\& | De referentie naar een 32-bit ondertekende gehele getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie gelukt is, anders - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) methode


Converteert de opgegeven tekenreeks met de stringrepresentatie van een getal naar het overeenkomstige 32-bit ondertekende gehele getal met behulp van de verstrekte opmaakinformatie en getalstijl.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De tekenreeks die moet worden geconverteerd. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de stringrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |
| result | **int32_t**\& | De referentie naar een 32-bit ondertekende gehele getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie gelukt is, anders - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) methode




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) methode




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) methode




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int32](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)