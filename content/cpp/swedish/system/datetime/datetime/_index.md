---
title: DateTime()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en instans som representerar det minsta möjliga datum- och tidsvärdet lika med MinValue.
type: docs
weight: 1
url: /sv/system/datetime/datetime/
---
## DateTime::DateTime() konstruktor


Skapar en instans som representerar det minsta möjliga datum- och tidsvärdet lika med MinValue.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad och dag.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad och dag i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendern som används för att tolka det specificerade **året**, **månaden** och **dagen**. |

## DateTime::DateTime(int, int, int, int, int, int) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad, dag, timme, minut och sekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| hour | int | Timmen i **dagen** som ska representeras av den instans som byggs. |
| minute | int | Minuten i **timm e** som ska representeras av den instans som byggs. |
| second | int | Sekunden i **minuten** som ska representeras av den instans som byggs. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad, dag, timme, minut och sekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| hour | int | Timmen i **dagen** som ska representeras av den instans som byggs. |
| minute | int | Minuten i **timm e** som ska representeras av den instans som byggs. |
| second | int | Sekunden i **minuten** som ska representeras av den instans som byggs. |
| kind | [DateTimeKind](../../datetimekind/) | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar lokal tid, UTC-tid eller ingen av dem. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad, dag, timme, minut och sekund i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| hour | int | Timmen i **dagen** som ska representeras av den instans som byggs. |
| minute | int | Minuten i **timm e** som ska representeras av den instans som byggs. |
| second | int | Sekunden i **minuten** som ska representeras av den instans som byggs. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Kalendern som används för att tolka det specificerade **året**, **månaden** och **dagen**. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad, dag, timme, minut, sekund och millisekund.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| hour | int | Timmen i **dagen** som ska representeras av den instans som byggs. |
| minute | int | Minuten i **timm e** som ska representeras av den instans som byggs. |
| second | int | Sekunden i **minuten** som ska representeras av den instans som byggs. |
| millisecond | int | Millisekunden i **sekunden** som ska representeras av den instans som byggs. |
| kind | [DateTimeKind](../../datetimekind/) | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar lokal tid, UTC-tid eller ingen av dem. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges med ett specifikt år, månad, dag, timme, minut, sekund och millisekund i den angivna kalendern.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| year | int | Året som ska representeras av den instans som byggs. |
| month | int | Månaden i **året** som ska representeras av den instans som byggs. |
| day | int | Dagen i **månaden** som ska representeras av den instans som byggs. |
| hour | int | Timmen i **dagen** som ska representeras av den instans som byggs. |
| minute | int | Minuten i **timm e** som ska representeras av den instans som byggs. |
| second | int | Sekunden i **minuten** som ska representeras av den instans som byggs. |
| millisecond | int | Millisekunden i **sekunden** som ska representeras av den instans som byggs. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Värdet som indikerar om de angivna datum- och tidsparametrarna specificerar lokal tid, UTC-tid eller ingen av dem. |
| calendar | [DateTimeKind](../../datetimekind/) | Kalendern som används för att tolka det specificerade **året**, **månaden** och **dagen**. |

## DateTime::DateTime(int64_t, DateTimeKind) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges som ett antal tick-intervall.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ticks | **int64_t** | Antalet 100-ns-intervall som har passerat sedan 1 januari 0001 00:00:00.000 i den gregorianska kalendern. |
| kind | [DateTimeKind](../../datetimekind/) | Värdet som indikerar om **ticks**-parametern specificerar lokal tid, UTC-tid eller ingen av dem. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) konstruktor


Skapar en instans som representerar ett datum- och tidsvärde som anges som ett antal tick-intervall. FÖR INTERNT BRUK.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ticks | **int64_t** | Antalet 100-ns-intervall som har passerat sedan 1 januari 0001 00:00:00.000 i den gregorianska kalendern. |
| kind | [DateTimeKind](../../datetimekind/) | Värdet som indikerar om **ticks**-parametern specificerar lokal tid, UTC-tid eller ingen av dem. |
| is_ambiguous_local_dst | **bool** | Sant om det angivna datumet och tiden är tvetydig och kan avbildas till många UTC-tider. |

## DateTime::DateTime(const DateTime\&) konstruktor


Kopierar en instans.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dt | const [DateTime](../)\& | En instans av klassen [DateTime](../) att kopiera det representerade datum- och tidsvärdet från |

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)