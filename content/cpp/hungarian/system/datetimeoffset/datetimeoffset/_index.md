---
title: DateTimeOffset()
second_title: Aspose.Slides for C++ API hivatkozás
description: Alapértelmezett konstruktor.
type: docs
weight: 1
url: /hu/system/datetimeoffset/datetimeoffset/
---
## DateTimeOffset::DateTimeOffset() konstruktor

Alapértelmezett konstruktor.

```cpp
constexpr System::DateTimeOffset::DateTimeOffset()=default
```

## DateTimeOffset::DateTimeOffset(DateTime) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Dátum és idő. |

## DateTimeOffset::DateTimeOffset(int64_t, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int64_t ticks, TimeSpan offset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ticks | **int64_t** | A tickek száma. |
| offset | [TimeSpan](../../timespan/) | Az UTC-hez viszonyított időeltolás. |

## DateTimeOffset::DateTimeOffset(DateTime, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(DateTime date_time, TimeSpan offset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| date_time | [DateTime](../../datetime/) | Dátum és idő. |
| offset | [TimeSpan](../../timespan/) | Az UTC-hez viszonyított időeltolás. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, TimeSpan offset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Év (1-től 9999-ig). |
| month | int | Hónap (1-től 12-ig). |
| day | int | Nap (1-től a hónap napjainak számáig). |
| hour | int | Óra (0-tól 23-ig). |
| minute | int | Perc (0-tól 59-ig). |
| second | int | Másodperc (0-tól 59-ig). |
| offset | [TimeSpan](../../timespan/) | Az UTC-hez viszonyított időeltolás. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, TimeSpan offset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Év (1-től 9999-ig). |
| month | int | Hónap (1-től 12-ig). |
| day | int | Nap (1-től a hónap napjainak számáig). |
| hour | int | Óra (0-tól 23-ig). |
| minute | int | Perc (0-tól 59-ig). |
| second | int | Másodperc (0-tól 59-ig). |
| millisecond | int | Miliszekundum (0-tól 999-ig). |
| offset | [TimeSpan](../../timespan/) | Az UTC-hez viszonyított időeltolás. |

## DateTimeOffset::DateTimeOffset(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) konstruktor

Konstruktor.

```cpp
System::DateTimeOffset::DateTimeOffset(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, TimeSpan offset)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Év. |
| month | int | Hónap (1-től 12-ig). |
| day | int | Nap (1-től a hónap napjainak számáig). |
| hour | int | Óra (0-tól 23-ig). |
| minute | int | Perc (0-tól 59-ig). |
| second | int | Másodperc (0-tól 59-ig). |
| millisecond | int | Miliszekundum (0-tól 999-ig). |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Az év, hónap és nap értelmezéséhez használt naptár. |
| offset | [TimeSpan](../../timespan/) | Az UTC-hez viszonyított időeltolás. |

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [DateTimeOffset](../)
* Osztály [DateTime](../../datetime/)
* Osztály [TimeSpan](../../timespan/)
* Osztály [Calendar](../../../system.globalization/calendar/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)