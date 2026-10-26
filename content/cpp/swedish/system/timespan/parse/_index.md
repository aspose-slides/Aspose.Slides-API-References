---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar strängen till motsvarande TimeSpan-objekt.
type: docs
weight: 534
url: /sv/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) metod


Konverterar strängen till motsvarande [TimeSpan](../)-objekt.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | Indatasträng. |

### Returvärde

Tidsintervall som motsvarar strängen.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar strängen till motsvarande [TimeSpan](../)-objekt med den angivna formatleverantören.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | Indatasträng. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör som tillhandahåller kulturberoende formateringsinformation. |

### Returvärde

Tidsintervall som motsvarar strängen.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metod




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) metod




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [TimeSpan](../)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)