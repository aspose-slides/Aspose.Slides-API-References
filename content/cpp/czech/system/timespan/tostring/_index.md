---
title: ToString()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací řetězcové znázornění časového intervalu reprezentovaného aktuálním objektem.
type: docs
weight: 261
url: /cs/system/timespan/tostring/
---
## TimeSpan::ToString() const metoda

Vrací řetězcové znázornění časového intervalu reprezentovaného aktuálním objektem.

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const metoda

Převádí hodnotu aktuálního objektu na ekvivalentní řetězcové znázornění pomocí zadaného formátu.

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda

Převádí hodnotu aktuálního objektu na ekvivalentní řetězcové znázornění pomocí zadaného formátu a poskytovatele formátu.

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
## Viz také

* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [TimeSpan](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)