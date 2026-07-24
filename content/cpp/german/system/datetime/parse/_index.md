---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwerts in das entsprechende DateTime-Objekt.
type: docs
weight: 859
url: /de/system/datetime/parse/
---
## DateTime::Parse(const String\&) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwerts in das entsprechende [DateTime](../)-Objekt.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwerts, der konvertiert werden soll. |

### Rückgabewert

Eine neue Instanz der Klasse [DateTime](../), die den durch die angegebene Zeichenkette dargestellten Datums- und Uhrzeitwert repräsentiert.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) Methode


Konvertiert die angegebene Zeichenkettenrepräsentation eines Datums- und Uhrzeitwerts in das entsprechende [DateTime](../)-Objekt unter Verwendung kulturspezifischer Formatinformationen.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | const [String](../../string/)\& | Die Zeichenkettenrepräsentation eines Datums- und Uhrzeitwerts, der konvertiert werden soll. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das [IFormatProvider](../../iformatprovider/)-Objekt, das kulturspezifische Formatinformationen bereitstellt. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Eine bitweise Kombination der Aufzählungswerte, die zusätzliche Informationen über **s**, über mögliche Stilelemente in **s** oder über die Konvertierung von **s** in ein [DateTime](../)-Objekt liefert. |

### Rückgabewert

Eine neue Instanz der Klasse [DateTime](../), die den durch die angegebene Zeichenkette dargestellten Datums- und Uhrzeitwert repräsentiert.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) Methode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) Methode




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) Methode




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Siehe auch

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTime](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)