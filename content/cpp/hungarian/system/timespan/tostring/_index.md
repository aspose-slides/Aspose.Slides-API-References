---
title: ToString()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja a jelenlegi objektum által reprezentált időintervallum karakterlánc ábrázolását.
type: docs
weight: 261
url: /hu/system/timespan/tostring/
---
## TimeSpan::ToString() const metódus

Visszaadja a jelenlegi objektum által reprezentált időintervallum karakterlánc ábrázolását.

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const metódus

Átalakítja a jelenlegi objektum értékét ekvivalens karakterlánc ábrázolássá a megadott formátum használatával.

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metódus

Átalakítja a jelenlegi objektum értékét ekvivalens karakterlánc ábrázolássá a megadott formátum és formátum szolgáltató használatával.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metódus




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metódus




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```
## TimeSpan::ToString(const String\&, std::nullptr_t) const metódus




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```
## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [TimeSpan](../)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)