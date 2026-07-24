---
title: Subtract()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine neue Instanz der DateTime-Klasse zurück, die den Datums- und Zeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls von dem durch das aktuelle Objekt dargestellten Wert ist.
type: docs
weight: 326
url: /de/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const Methode

Gibt eine neue Instanz der [DateTime](../) Klasse zurück, die den Datums- und Zeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls vom durch das aktuelle Objekt dargestellten Wert ist.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Ein Zeitintervall zum Subtrahieren |

### Rückgabewert

Eine neue Instanz der [DateTime](../) Klasse, die den Datums- und Zeitwert darstellt, der das Ergebnis der Subtraktion von **duration** vom durch das aktuelle Objekt dargestellten Wert ist.

## DateTime::Subtract(DateTime) const Methode

Gibt eine Instanz der [TimeSpan](../../timespan/) Klasse zurück, die das Zeitintervall zwischen den durch das aktuelle und das angegebene Objekt dargestellten Datums- und Zeitwerten darstellt.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DateTime](../) | Eine Instanz der [DateTime](../) Klasse, die ein Ende des zu berechnenden Intervalls markiert |

### Rückgabewert

Eine Instanz der [TimeSpan](../../timespan/) Klasse, die das Zeitintervall zwischen den durch das aktuelle Objekt und **value** dargestellten Datums- und Zeitwerten darstellt.

## Siehe auch

* Klasse [DateTime](../)
* Klasse [TimeSpan](../../timespan/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)