---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ondertekende geheel getal.
type: docs
weight: 1
url: /nl/system/int32/parse/
---
## Int32::Parse(const String\&) methode

Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ondertekende geheel getal.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |

### Retourwaarde

Het 32-bit ondertekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ondertekende geheel getal met behulp van de verstrekte opmaakinformatie.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat. |

### Retourwaarde

Het 32-bit ondertekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) methode

```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het equivalente 32-bit ondertekende geheel getal met behulp van de verstrekte opmaakinformatie en nummerstijl.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat. |

### Retourwaarde

Het 32-bit ondertekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Int32](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasse [ReadOnlySpan](../../readonlyspan/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)