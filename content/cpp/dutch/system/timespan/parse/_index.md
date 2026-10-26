---
title: Parse()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert een string naar een equivalent TimeSpan object.
type: docs
weight: 534
url: /nl/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) methode

Converteert een string naar een equivalent [TimeSpan](../) object.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | Invoertekst. |

### Retourwaarde

Tijdsinterval dat overeenkomt met de string.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert een string naar een equivalent [TimeSpan](../) object met behulp van de opgegeven formatprovider.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | Invoertekst. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider die cultuur-specifieke opmaakinformatie levert. |

### Retourwaarde

Tijdsinterval dat overeenkomt met de string.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) methode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) methode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Zie Ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [TimeSpan](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)