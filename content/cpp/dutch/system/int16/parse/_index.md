---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 16-bit ondertekende geheel getal.
type: docs
weight: 1
url: /nl/system/int16/parse/
---
## Int16::Parse(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 16-bit ondertekende geheel getal.

```cpp
static int16_t System::Int16::Parse(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |

### Retourwaarde

Het 16-bit ondertekende geheel getal gelijk aan het getal dat wordt weergegeven door de opgegeven string.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 16-bit ondertekende geheel getal met behulp van de opgegeven opmaakinformatie.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 16-bit ondertekende geheel getal gelijk aan het getal dat wordt weergegeven door de opgegeven string.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode


```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode


```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) methode


```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 16-bit ondertekende geheel getal met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 16-bit ondertekende geheel getal gelijk aan het getal dat wordt weergegeven door de opgegeven string.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode


```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode


```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode


```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int16](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)