---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichenketten-Darstellung des vom aktuellen Objekt dargestellten Zeitintervalls zurück.
type: docs
weight: 261
url: /de/system/timespan/tostring/
---
## TimeSpan::ToString() const method

Gibt die Zeichenketten-Darstellung des vom aktuellen Objekt dargestellten Zeitintervalls zurück.

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const method

Konvertiert den Wert des aktuellen Objekts in eine äquivalente Zeichenketten-Darstellung, wobei das angegebene Format verwendet wird.

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method

Konvertiert den Wert des aktuellen Objekts in eine äquivalente Zeichenketten-Darstellung, wobei das angegebene Format und der Format-Provider verwendet werden.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```
## TimeSpan::ToString(const String\&, std::nullptr_t) const method




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```
## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [TimeSpan](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)