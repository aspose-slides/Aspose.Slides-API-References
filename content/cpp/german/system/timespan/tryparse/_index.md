---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert eine Zeichenkette in das entsprechende TimeSpan-Objekt und gibt das Ergebnis der Konvertierung zurück.
type: docs
weight: 560
url: /de/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) Methode


Konvertiert die Zeichenkette in das entsprechende [TimeSpan](../)-Objekt und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

True, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) Methode


Konvertiert die Zeichenkette in das entsprechende [TimeSpan](../)-Objekt unter Verwendung des angegebenen Formatproviders und gibt das Ergebnis der Konvertierung zurück.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabezeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formatprovider, der kulturspezifische Formatinformationen bereitstellt. |
| result | [TimeSpan](../)\& | Zeitintervall, das der Zeichenkette entspricht. |

### Rückgabewert

True, wenn die Zeichenkette erfolgreich konvertiert wurde; andernfalls false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) Methode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) Methode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) Methode




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Siehe Auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [TimeSpan](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)