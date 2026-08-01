---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het gelijkwaardige 16-bit unsigned integer.
type: docs
weight: 1
url: /nl/system/uint16/parse/
---
## UInt16::Parse(const String\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het gelijkwaardige 16-bit unsigned integer.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |

### Retourwaarde

Het 16-bit unsigned integer dat gelijk is aan het door de opgegeven string vertegenwoordigde getal.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het gelijkwaardige 16-bit unsigned integer met behulp van de opgegeven opmaakinformatie.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 16-bit unsigned integer dat gelijk is aan het door de opgegeven string vertegenwoordigde getal.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) methode




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het gelijkwaardige 16-bit unsigned integer met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 16-bit unsigned integer dat gelijk is aan het door de opgegeven string vertegenwoordigde getal.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode 




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode 




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)