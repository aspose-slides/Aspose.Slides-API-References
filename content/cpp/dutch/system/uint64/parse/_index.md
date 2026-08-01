---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar het overeenkomstige 64-bit ongetekende gehele getal.
type: docs
weight: 1
url: /nl/system/uint64/parse/
---
## UInt64::Parse(const String\&) methode


Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar het overeenkomstige 64-bit ongetekende geheel getal.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |

### Retourwaarde

Het 64-bit ongetekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar het overeenkomstige 64-bit ongetekende geheel getal met behulp van de verstrekte opmaakinformatie.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat. |

### Retourwaarde

Het 64-bit ongetekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven tekenreeks die de tekstuele weergave van een getal bevat naar het overeenkomstige 64-bit ongetekende geheel getal met behulp van de verstrekte opmaakinformatie en de getalstijl.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekstuele weergave van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat. |

### Retourwaarde

Het 64-bit ongetekende geheel getal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven tekenreeks.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)