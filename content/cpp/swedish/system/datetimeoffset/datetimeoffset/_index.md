---
title: DateTimeOffset()
second_title: Aspose.Slides för C++ API-referens
description: Standardkonstruktor.
type: docs
weight: 1
url: /sv/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() konstruktor

Standardkonstruktor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ticks | **int64_t** | Antal tick. |
| offset | [TimeSpan](../../timespan/) | Tidsförskjutning från UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Datum och tid. |
| offset | [TimeSpan](../../timespan/) | Tidsförskjutning från UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | År (1 till 9999). |
| month | int | Månad (1 till 12). |
| day | int | Dag (1 till antalet dagar i månaden). |
| hour | int | Timme (0 till 23). |
| minute | int | Minut (0 till 59). |
| second | int | Sekund (0 till 59). |
| offset | [TimeSpan](../../timespan/) | Tidsförskjutning från UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | År (1 till 9999). |
| month | int | Månad (1 till 12). |
| day | int | Dag (1 till antalet dagar i månaden). |
| hour | int | Timme (0 till 23). |
| minute | int | Minut (0 till 59). |
| second | int | Sekund (0 till 59). |
| millisecond | int | Millisekund (0 till 999). |
| offset | [TimeSpan](../../timespan/) | Tidsförskjutning från UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | År. |
| month | int | Månad (1 till 12). |
| day | int | Dag (1 till antalet dagar i månaden). |
| hour | int | Timme (0 till 23). |
| minute | int | Minut (0 till 59). |
| second | int | Sekund (0 till 59). |
| millisecond | int | Millisekund (0 till 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalender som används för att tolka år, månad och dag. |
| offset | [TimeSpan](../../timespan/) | Tidsförskjutning från UTC. |

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [DateTimeOffset](../)
* Klass [DateTime](../../datetime/)
* Klass [TimeSpan](../../timespan/)
* Klass [Calendar](../../../system.globalization/calendar/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)