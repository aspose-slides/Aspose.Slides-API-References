---
title: TryParse()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende DateTime-Objekt.
type: docs
weight: 885
url: /de/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende [DateTime](../)-Objekt.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, der konvertiert werden soll. |
| result | [DateTime](../)\& | Das Ausgabeargument, das bei erfolgreicher Konvertierung das Ergebnis der Konvertierung enthält. |

### Return Value

True, wenn die Konvertierung erfolgreich ist, andernfalls - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes in das entsprechende [DateTime](../)-Objekt unter Verwendung der angegebenen kulturspezifischen Formatinformationen und des Stils.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwertes, der konvertiert werden soll. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Enumerationswerte, die zusätzliche Informationen über **s**, über eventuell in **s** vorhandene Stilelemente oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt bereitstellt. |
| result | [DateTime](../)\& | Das Ausgabeargument, das bei erfolgreicher Konvertierung das Ergebnis der Konvertierung enthält. |

### Return Value

True, wenn die Konvertierung erfolgreich ist, andernfalls - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode


```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) Methode


```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) Methode


```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Siehe auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [DateTime](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)