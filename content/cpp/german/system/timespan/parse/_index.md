---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Zeichenkette in das entsprechende TimeSpan-Objekt.
type: docs
weight: 534
url: /de/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) Methode

Konvertiert die Zeichenkette in das entsprechende [TimeSpan](../)-Objekt.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabe-Zeichenkette. |

### Rückgabewert

Zeitintervall, das der Zeichenkette entspricht.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die Zeichenkette in das entsprechende [TimeSpan](../)-Objekt unter Verwendung des angegebenen Format-Providers.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | const [String](../../string/)\& | Eingabe-Zeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format-Provider, der kulturspezifische Formatierungsinformationen bereitstellt. |

### Rückgabewert

Zeitintervall, das der Zeichenkette entspricht.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) Methode

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) Methode

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [TimeSpan](../)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)