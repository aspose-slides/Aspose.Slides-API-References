---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een string naar het equivalente TimeSpan-object en retourneert het resultaat van de conversie.
type: docs
weight: 560
url: /nl/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) method


Converteert een string naar het equivalente [TimeSpan](../)-object en retourneert het resultaat van de conversie.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| result | [TimeSpan](../)\& | Time interval that corresponds to string. |

### Retourwaarde

True als de string succesvol is geconverteerd; anders false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Converteert een string naar het equivalente [TimeSpan](../)-object met de opgegeven formatprovider en retourneert het resultaat van de conversie.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../string/)\& | Input string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format provider that supplies culture-specific formatting information. |
| result | [TimeSpan](../)\& | Time interval that corresponds to string. |

### Retourwaarde

True als de string succesvol is geconverteerd; anders false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [TimeSpan](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)