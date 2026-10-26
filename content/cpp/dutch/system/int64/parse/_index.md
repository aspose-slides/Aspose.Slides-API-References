---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar het equivalente 64-bit ondertekende gehele integer.
type: docs
weight: 1
url: /nl/system/int64/parse/
---
## Int64::Parse(const String\&) methode


Converteert de opgegeven string met de tekenreeksrepresentatie van een getal naar het equivalente 64-bits ondertekende gehele getal.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |

### Retourwaarde

Het 64-bits ondertekende gehele getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string met de tekenreeksrepresentatie van een getal naar het equivalente 64-bits ondertekende gehele getal met behulp van de meegeleverde opmaakinformatie.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 64-bits ondertekende gehele getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) methode




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string met de tekenreeksrepresentatie van een getal naar het equivalente 64-bits ondertekende gehele getal met behulp van de meegeleverde opmaakinformatie en het getalstijl.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |

### Retourwaarde

Het 64-bits ondertekende gehele getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode 




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode 




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int64](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)