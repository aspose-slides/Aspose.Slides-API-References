---
title: DateTimeOffset()
second_title: Aspose.Slides pro C++ API Reference
description: Výchozí konstruktor.
type: docs
weight: 1
url: /cs/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() konstruktor


Výchozí konstruktor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ticks | **int64_t** | Počet tiků. |
| offset | [TimeSpan](../../timespan/) | Časový posun od UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum a čas. |
| offset | [TimeSpan](../../timespan/) | Časový posun od UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok (1 až 9999). |
| month | int | Měsíc (1 až 12). |
| day | int | Den (1 až počet dnů v měsíci). |
| hour | int | Hodina (0 až 23). |
| minute | int | Minuta (0 až 59). |
| second | int | Sekunda (0 až 59). |
| offset | [TimeSpan](../../timespan/) | Časový posun od UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok (1 až 9999). |
| month | int | Měsíc (1 až 12). |
| day | int | Den (1 až počet dnů v měsíci). |
| hour | int | Hodina (0 až 23). |
| minute | int | Minuta (0 až 59). |
| second | int | Sekunda (0 až 59). |
| millisecond | int | Milisekunda (0 až 999). |
| offset | [TimeSpan](../../timespan/) | Časový posun od UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) konstruktor


Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| year | int | Rok. |
| month | int | Měsíc (1 až 12). |
| day | int | Den (1 až počet dnů v měsíci). |
| hour | int | Hodina (0 až 23). |
| minute | int | Minuta (0 až 59). |
| second | int | Sekunda (0 až 59). |
| millisecond | int | Milisekunda (0 až 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendář použitý k interpretaci roku, měsíce a dne. |
| offset | [TimeSpan](../../timespan/) | Časový posun od UTC. |

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [DateTimeOffset](../)
* Třída [DateTime](../../datetime/)
* Třída [TimeSpan](../../timespan/)
* Třída [Calendar](../../../system.globalization/calendar/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)