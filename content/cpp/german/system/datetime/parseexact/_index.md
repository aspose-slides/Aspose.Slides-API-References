---
title: ParseExact()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende DateTime-Objekt unter Verwendung des angegebenen Formats und kulturspezifischer Formatinformationen. Das Format der Zeichenkettenrepräsentation muss exakt dem angegebenen Format entsprechen. Wirft eine Ausnahme, wenn die Konvertierung fehlschlägt.
type: docs
weight: 872
url: /de/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode

Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende [DateTime](../)-Objekt unter Verwendung des angegebenen Formats und kulturspezifischer Formatinformationen. Das Format der Zeichenkettenrepräsentation muss exakt dem angegebenen Format entsprechen. Wirft eine Ausnahme, wenn die Konvertierung fehlschlägt.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, die konvertiert werden soll. |
| format | const [String](../../string/)\& | Das Zeichenkettenformat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Enumerationswerte, die zusätzliche Informationen über **s**, über mögliche Stilelemente in **s** oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt liefert. |

### Rückgabewert

Eine neue Instanz der [DateTime](../)-Klasse, die den Datums- und Uhrzeitwert darstellt, der dem durch die angegebene Zeichenkette dargestellten entspricht.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode

Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende [DateTime](../)-Objekt unter Verwendung der angegebenen Formate, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettenrepräsentation muss exakt einem oder mehreren der angegebenen Formate entsprechen. Wirft eine Ausnahme, wenn die Konvertierung fehlschlägt.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, die konvertiert werden soll. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Das Array von Zeichenkettenformaten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Enumerationswerte, die zusätzliche Informationen über **s**, über mögliche Stilelemente in **s** oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt liefert. |

### Rückgabewert

Eine neue Instanz der [DateTime](../)-Klasse, die den Datums- und Uhrzeitwert darstellt, der dem durch die angegebene Zeichenkette dargestellten entspricht.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) Methode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Siehe auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [DateTime](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)