---
title: TimeSpan()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert ein TimeSpan-Objekt, das ein Zeitintervall von null darstellt.
type: docs
weight: 1
url: /de/system/timespan/timespan/
---
## TimeSpan::TimeSpan() Konstruktor


Erstellt ein [TimeSpan](../)-Objekt, das ein Zeitintervall von null darstellt.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) Konstruktor


Erstellt eine Instanz der Klasse [TimeSpan](../), die das angegebene Zeitintervall darstellt.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | **int64_t** | Das Zeitintervall, das durch die zu erstellende Instanz dargestellt wird, angegeben als Anzahl von 100-Nanosekunden-Intervallen. |

## TimeSpan::TimeSpan(int, int, int) Konstruktor


Erstellt eine Instanz der Klasse [TimeSpan](../), die das Zeitintervall darstellt, das der Summe der angegebenen Stunden, Minuten und Sekunden entspricht.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hours | int | Die Anzahl der Stunden im Stunden-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| minutes | int | Die Anzahl der Minuten im Minuten-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| seconds | int | Die Anzahl der Sekunden im Sekunden-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |

## TimeSpan::TimeSpan(int, int, int, int, int) Konstruktor


Erstellt eine Instanz der Klasse [TimeSpan](../), die das Zeitintervall darstellt, das der Summe der angegebenen Stunden, Minuten, Sekunden und Millisekunden entspricht.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| days | int | Die Anzahl der Tage im Tage-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| hours | int | Die Anzahl der Stunden im Stunden-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| minutes | int | Die Anzahl der Minuten im Minuten-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| seconds | int | Die Anzahl der Sekunden im Sekunden-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |
| milliseconds | int | Die Anzahl der Millisekunden im Millisekunden-Teil des Zeitintervalls, das durch die zu erstellende Instanz dargestellt wird |

## TimeSpan::TimeSpan(const TimeSpan\&) Konstruktor


Erstellt ein [TimeSpan](../)-Objekt, das das Zeitintervall darstellt, das dem von dem angegebenen [TimeSpan](../)-Objekt dargestellten Zeitintervall entspricht.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Siehe auch

* Klasse [TimeSpan](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)