---
title: DateTimeOffset()
second_title: Aspose.Slides dla C++ - Referencja API
description: Domyślny konstruktor.
type: docs
weight: 1
url: /pl/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() konstruktor

Domyślny konstruktor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data i godzina. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ticks | **int64_t** | Liczba tików. |
| offset | [TimeSpan](../../timespan/) | Przesunięcie czasu względem UTC. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Data i godzina. |
| offset | [TimeSpan](../../timespan/) | Przesunięcie czasu względem UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok (od 1 do 9999). |
| month | int | Miesiąc (od 1 do 12). |
| day | int | Dzień (od 1 do liczby dni w miesiącu). |
| hour | int | Godzina (od 0 do 23). |
| minute | int | Minuta (od 0 do 59). |
| second | int | Sekunda (od 0 do 59). |
| offset | [TimeSpan](../../timespan/) | Przesunięcie czasu względem UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok (od 1 do 9999). |
| month | int | Miesiąc (od 1 do 12). |
| day | int | Dzień (od 1 do liczby dni w miesiącu). |
| hour | int | Godzina (od 0 do 23). |
| minute | int | Minuta (od 0 do 59). |
| second | int | Sekunda (od 0 do 59). |
| millisecond | int | Milisekunda (od 0 do 999). |
| offset | [TimeSpan](../../timespan/) | Przesunięcie czasu względem UTC. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| year | int | Rok. |
| month | int | Miesiąc (od 1 do 12). |
| day | int | Dzień (od 1 do liczby dni w miesiącu). |
| hour | int | Godzina (od 0 do 23). |
| minute | int | Minuta (od 0 do 59). |
| second | int | Sekunda (od 0 do 59). |
| millisecond | int | Milisekunda (od 0 do 999). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendarz używany do interpretacji roku, miesiąca i dnia. |
| offset | [TimeSpan](../../timespan/) | Przesunięcie czasu względem UTC. |

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Klasa [DateTimeOffset](../)
* Klasa [DateTime](../../datetime/)
* Klasa [TimeSpan](../../timespan/)
* Klasa [Calendar](../../../system.globalization/calendar/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)