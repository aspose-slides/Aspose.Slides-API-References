---
title: operator-()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine neue Instanz der DateTimeOffset-Klasse zurück, die den Datum- und Uhrzeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls vom vom aktuellen Objekt dargestellten Wert ist.
type: docs
weight: 521
url: /de/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const Methode


Gibt eine neue Instanz der [DateTimeOffset](../)-Klasse zurück, die den Datum- und Uhrzeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls vom vom aktuellen Objekt dargestellten Wert ist.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Ein Zeitintervall zum Subtrahieren |

### Rückgabewert

Eine neue Instanz der [DateTimeOffset](../)-Klasse, die den Datum- und Uhrzeitwert darstellt, der das Ergebnis der Subtraktion von **value** vom vom aktuellen Objekt dargestellten Wert ist.

## DateTimeOffset::operator-(const DateTimeOffset\&) const Methode


Gibt eine Instanz der [TimeSpan](../../timespan/)-Klasse zurück, die das Zeitintervall zwischen den von dem aktuellen und dem angegebenen Objekt dargestellten Datum- und Uhrzeitwerten repräsentiert.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Eine Instanz der [DateTime](../../datetime/)-Klasse, die ein Ende des zu berechnenden Intervalls markiert |

### Rückgabewert

Eine Instanz der [TimeSpan](../../timespan/)-Klasse, die das Zeitintervall zwischen den von dem aktuellen Objekt und **other** dargestellten Datum- und Uhrzeitwerten darstellt.

## Siehe auch

* Klasse [DateTimeOffset](../)
* Klasse [TimeSpan](../../timespan/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)