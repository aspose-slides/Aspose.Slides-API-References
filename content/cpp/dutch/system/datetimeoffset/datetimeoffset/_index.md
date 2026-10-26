---
title: DateTimeOffset()
second_title: Aspose.Slides voor C++ API-referentie
description: Standaardconstructor.
type: docs
weight: 1
url: /nl/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() constructor


Standaardconstructor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum en tijd. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ticks | **int64_t** | Aantal ticks. |
| offset | [TimeSpan](../../timespan/) | Tijdverschuiving ten opzichte van UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum en tijd. |
| offset | [TimeSpan](../../timespan/) | Tijdverschuiving ten opzichte van UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Jaar (1 tot en met 9999). |
| month | int | Maand (1 tot en met 12). |
| day | int | Dag (1 tot en met het aantal dagen in de maand). |
| hour | int | Uur (0 tot en met 23). |
| minute | int | Minuut (0 tot en met 59). |
| second | int | Seconde (0 tot en met 59). |
| offset | [TimeSpan](../../timespan/) | Tijdverschuiving ten opzichte van UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Jaar (1 tot en met 9999). |
| month | int | Maand (1 tot en met 12). |
| day | int | Dag (1 tot en met het aantal dagen in de maand). |
| hour | int | Uur (0 tot en met 23). |
| minute | int | Minuut (0 tot en met 59). |
| second | int | Seconde (0 tot en met 59). |
| millisecond | int | Milliseconde (0 tot en met 999). |
| offset | [TimeSpan](../../timespan/) | Tijdverschuiving ten opzichte van UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) constructor


Constructor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| year | int | Jaar. |
| month | int | Maand (1 tot en met 12). |
| day | int | Dag (1 tot en met het aantal dagen in de maand). |
| hour | int | Uur (0 tot en met 23). |
| minute | int | Minuut (0 tot en met 59). |
| second | int | Seconde (0 tot en met 59). |
| millisecond | int | Milliseconde (0 tot en met 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender die wordt gebruikt om jaar, maand en dag te interpreteren. |
| offset | [TimeSpan](../../timespan/) | Tijdverschuiving ten opzichte van UTC. |

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [DateTime](../../datetime/)
* Class [TimeSpan](../../timespan/)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)