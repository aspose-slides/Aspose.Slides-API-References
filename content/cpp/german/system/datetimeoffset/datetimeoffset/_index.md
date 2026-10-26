---
title: DateTimeOffset()
second_title: Aspose.Slides für C++ API Referenz
description: Standardkonstruktor.
type: docs
weight: 1
url: /de/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() Konstruktor

Standardkonstruktor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum und Uhrzeit. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ticks | **int64_t** | Anzahl der Ticks. |
| offset | [TimeSpan](../../timespan/) | Zeitversatz von UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum und Uhrzeit. |
| offset | [TimeSpan](../../timespan/) | Zeitversatz von UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Jahr (1 bis 9999). |
| month | int | Monat (1 bis 12). |
| day | int | Tag (1 bis zur Anzahl der Tage im Monat). |
| hour | int | Stunde (0 bis 23). |
| minute | int | Minute (0 bis 59). |
| second | int | Sekunde (0 bis 59). |
| offset | [TimeSpan](../../timespan/) | Zeitversatz von UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Jahr (1 bis 9999). |
| month | int | Monat (1 bis 12). |
| day | int | Tag (1 bis zur Anzahl der Tage im Monat). |
| hour | int | Stunde (0 bis 23). |
| minute | int | Minute (0 bis 59). |
| second | int | Sekunde (0 bis 59). |
| millisecond | int | Millisekunde (0 bis 999). |
| offset | [TimeSpan](../../timespan/) | Zeitversatz von UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) Konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| year | int | Jahr. |
| month | int | Monat (1 bis 12). |
| day | int | Tag (1 bis zur Anzahl der Tage im Monat). |
| hour | int | Stunde (0 bis 23). |
| minute | int | Minute (0 bis 59). |
| second | int | Sekunde (0 bis 59). |
| millisecond | int | Millisekunde (0 bis 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender, der zur Interpretation von Jahr, Monat und Tag verwendet wird. |
| offset | [TimeSpan](../../timespan/) | Zeitversatz von UTC. |

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [DateTimeOffset](../)
* Klasse [DateTime](../../datetime/)
* Klasse [TimeSpan](../../timespan/)
* Klasse [Calendar](../../../system.globalization/calendar/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)