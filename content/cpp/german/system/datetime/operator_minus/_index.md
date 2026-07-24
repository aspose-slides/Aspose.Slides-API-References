---
title: operator-()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine neue Instanz der DateTime-Klasse zurück, die den Datum- und Uhrzeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls vom vom aktuellen Objekt dargestellten Wert ist.
type: docs
weight: 651
url: /de/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const method

Gibt eine neue Instanz der [DateTime](../) Klasse zurück, die den Datum und Uhrzeitwert darstellt, der als Ergebnis der Subtraktion des angegebenen Zeitintervalls vom vom aktuellen Objekt dargestellten Wert entsteht.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Ein Zeitintervall, das subtrahiert werden soll |

### Rückgabewert

Eine neue Instanz der [DateTime](../) Klasse, die den Datum und Uhrzeitwert darstellt, der das Ergebnis der Subtraktion von **value** vom vom aktuellen Objekt dargestellten Wert ist.

## DateTime::operator-(DateTime) const method

Gibt eine Instanz der [TimeSpan](../../timespan/) Klasse zurück, die das Zeitintervall zwischen den von dem aktuellen und dem angegebenen Objekt dargestellten Datum und Uhrzeitwerten repräsentiert.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DateTime](../) | Eine Instanz der [DateTime](../) Klasse, die ein Ende des zu berechnenden Intervalls markiert |

### Rückgabewert

Eine Instanz der [TimeSpan](../../timespan/) Klasse, die das Zeitintervall zwischen den von dem aktuellen Objekt und **value** dargestellten Datum und Uhrzeitwerten darstellt.

## Siehe auch

* Klasse [DateTime](../)
* Klasse [TimeSpan](../../timespan/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)