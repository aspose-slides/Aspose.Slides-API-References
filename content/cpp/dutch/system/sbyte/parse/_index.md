---
title: Parse()
second_title: Aspose.Slides for C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bits ondertekende integer.
type: docs
weight: 1
url: /nl/system/sbyte/parse/
---
## SByte::Parse(const String\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bits ondertekende integer.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd. |

### Retourwaarde

De 8-bits ondertekende integer die gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bits ondertekende integer met behulp van de opgegeven opmaakinformatie.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat. |

### Retourwaarde

De 8-bits ondertekende integer die gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) methode.




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 8-bits ondertekende integer met behulp van de opgegeven opmaakinformatie en getalstijlen.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de stringrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat. |

### Retourwaarde

De 8-bits ondertekende integer die gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)