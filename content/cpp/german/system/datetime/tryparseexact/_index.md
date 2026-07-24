---
title: TryParseExact()
second_title: Aspose.Slides für C++ API-Referenz
description: Wandelt die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende DateTime-Objekt um, wobei das angegebene Format, kulturspezifische Formatinformationen und der Stil verwendet werden. Das Format der Zeichenkettenrepräsentation muss exakt dem angegebenen Format entsprechen.
type: docs
weight: 898
url: /de/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das äquivalente [DateTime](../)-Objekt unter Verwendung des angegebenen Formats, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettenrepräsentation muss exakt dem angegebenen Format entsprechen.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, die konvertiert werden soll. |
| format | const [String](../../string/)\& | Das Zeichenkettenformat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Aufzählungswerte, die zusätzliche Informationen über **s**, über Stilelemente, die in **s** vorhanden sein können, oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt bereitstellt. |
| result | [DateTime](../)\& | Das Ausgabeargument, das bei erfolgreicher Konvertierung das Ergebnis der Konvertierung enthält. |

### Rückgabewert

True, wenn die Konvertierung erfolgreich ist, andernfalls - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das äquivalente [DateTime](../)-Objekt unter Verwendung der angegebenen Formate, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettenrepräsentation muss exakt einem der angegebenen Formate entsprechen.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, die konvertiert werden soll. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Das Array von Zeichenkettenformaten. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Aufzählungswerte, die zusätzliche Informationen über **s**, über Stilelemente, die in **s** vorhanden sein können, oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt bereitstellt. |
| result | [DateTime](../)\& | Das Ausgabeargument, das bei erfolgreicher Konvertierung das Ergebnis der Konvertierung enthält. |

### Rückgabewert

True, wenn die Konvertierung erfolgreich ist, andernfalls - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) Methode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Siehe auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)