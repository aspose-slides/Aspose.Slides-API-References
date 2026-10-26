---
title: ToString()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca reprezentację łańcucha znaków przedziału czasu reprezentowanego przez bieżący obiekt.
type: docs
weight: 261
url: /pl/system/timespan/tostring/
---
## TimeSpan::ToString() const metoda

Zwraca reprezentację łańcucha znaków przedziału czasu reprezentowanego przez bieżący obiekt.

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const metoda

Konwertuje wartość bieżącego obiektu na równoważną reprezentację w postaci łańcucha znaków, używając określonego formatu.

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda

Konwertuje wartość bieżącego obiektu na równoważną reprezentację w postaci łańcucha znaków, używając określonego formatu i dostawcy formatu.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metoda




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```
## TimeSpan::ToString(const String\&, std::nullptr_t) const metoda




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
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