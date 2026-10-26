---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente enkelprecisie floating-point-waarde.
type: docs
weight: 1
url: /nl/system/single/parse/
---
## Single::Parse(const String\&) methode


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente enkelprecisie floating-point-waarde.

```cpp
static float System::Single::Parse(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |

### Returnwaarde

De enkelprecisie floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente enkelprecisie floating-point-waarde met behulp van de opgegeven opmaakinformatie.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaak-informatie bevat. |

### Returnwaarde

De enkelprecisie floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) methode




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar de equivalente enkelprecisie floating-point-waarde met behulp van de opgegeven opmaakinformatie en het opgegeven getalformaat.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaak-informatie bevat. |

### Returnwaarde

De enkelprecisie floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)