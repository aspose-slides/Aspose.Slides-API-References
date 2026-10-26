---
title: Parse()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konwertuje łańcuch znaków na równoważny obiekt TimeSpan.
type: docs
weight: 534
url: /pl/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) method

Konwertuje łańcuch znaków na równoważny obiekt [TimeSpan](../).

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |

### Wartość zwracana

Przedział czasu odpowiadający łańcuchowi.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Konwertuje łańcuch znaków na równoważny obiekt [TimeSpan](../) przy użyciu określonego dostawcy formatu.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Łańcuch wejściowy. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu, który dostarcza informacje o formatowaniu zależnym od kultury. |

### Wartość zwracana

Przedział czasu odpowiadający łańcuchowi.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) method




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [TimeSpan](../)
* Klasa [String](../../string/)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)