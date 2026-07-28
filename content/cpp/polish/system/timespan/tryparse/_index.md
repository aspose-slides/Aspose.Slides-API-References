---
title: TryParse()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje ciąg znaków na równoważny obiekt TimeSpan i zwraca wynik konwersji.
type: docs
weight: 560
url: /pl/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metoda


Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](../) i zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Ciąg znaków wejściowy. |
| result | [TimeSpan](../)\& | Przedział czasu odpowiadający ciągowi. |

### Wartość zwracana

Prawda, jeśli ciąg został pomyślnie skonwertowany; w przeciwnym razie fałsz.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metoda


Konwertuje ciąg znaków na równoważny obiekt [TimeSpan](../) przy użyciu określonego dostawcy formatu i zwraca wynik konwersji.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input | const [String](../../string/)\& | Ciąg znaków wejściowy. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu dostarczający informacje o formatowaniu zależnym od kultury. |
| result | [TimeSpan](../)\& | Przedział czasu odpowiadający ciągowi. |

### Wartość zwracana

Prawda, jeśli ciąg został pomyślnie skonwertowany; w przeciwnym razie fałsz.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metoda




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [TimeSpan](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)