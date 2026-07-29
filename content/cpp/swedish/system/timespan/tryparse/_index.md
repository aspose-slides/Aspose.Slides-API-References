---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar sträng till motsvarande TimeSpan-objekt och returnerar resultatet av konverteringen.
type: docs
weight: 560
url: /sv/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metod


Konverterar sträng till motsvarande [TimeSpan](../)-objekt och returnerar resultatet av konverteringen.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | Indatasträng. |
| result | [TimeSpan](../)\& | Tidsintervall som motsvarar strängen. |

### Return Value

True om strängen konverterades framgångsrikt; annars false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metod


Konverterar sträng till motsvarande [TimeSpan](../)-objekt med den angivna formatleverantören och returnerar resultatet av konverteringen.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../string/)\& | Indatasträng. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatleverantör som tillhandahåller kultur-specifik formateringsinformation. |
| result | [TimeSpan](../)\& | Tidsintervall som motsvarar strängen. |

### Return Value

True om strängen konverterades framgångsrikt; annars false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metod




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metod




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metod




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [TimeSpan](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)