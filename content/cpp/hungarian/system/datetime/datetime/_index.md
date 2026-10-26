---
title: DateTime()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy példányt, amely a legkisebb lehetséges dátum- és időértéket képviseli, amely egyenlő a MinValue-val.
type: docs
weight: 1
url: /hu/system/datetime/datetime/
---
## DateTime::DateTime() konstruktor


Létrehoz egy példányt, amely a legkisebb lehetséges dátum- és időértéket képviseli, amely egyenlő a MinValue-val.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) konstruktor


Létrehoz egy példányt, amely egy adott év, hónap és nap által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Létrehoz egy példányt, amely a megadott naptárban egy adott év, hónap és nap által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | A naptár, amely a megadott **year**, **month** és **day** értelmezésére szolgál. |

## DateTime::DateTime(int, int, int, int, int, int) konstruktor


Létrehoz egy példányt, amely egy adott év, hónap, nap, óra, perc és másodperc által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| hour | int | A **day** órája, amelyet a létrehozott példány képvisel. |
| minute | int | A **hour** perce, amelyet a létrehozott példány képvisel. |
| second | int | A **minute** másodperce, amelyet a létrehozott példány képvisel. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) konstruktor


Létrehoz egy példányt, amely egy adott év, hónap, nap, óra, perc és másodperc által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| hour | int | A **day** órája, amelyet a létrehozott példány képvisel. |
| minute | int | A **hour** perce, amelyet a létrehozott példány képvisel. |
| second | int | A **minute** másodperce, amelyet a létrehozott példány képvisel. |
| kind | [DateTimeKind](../../datetimekind/) | Az az érték, amely azt jelzi, hogy a megadott dátum- és időparaméterek helyi időt, UTC-t vagy egyikiket sem határoznak meg. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) konstruktor


Létrehoz egy példányt, amely a megadott naptárban egy adott év, hónap, nap, óra, perc és másodperc által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| hour | int | A **day** órája, amelyet a létrehozott példány képvisel. |
| minute | int | A **hour** perce, amelyet a létrehozott példány képvisel. |
| second | int | A **minute** másodperce, amelyet a létrehozott példány képvisel. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | A naptár, amely a megadott **year**, **month** és **day** értelmezésére szolgál. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) konstruktor


Létrehoz egy példányt, amely egy adott év, hónap, nap, óra, perc, másodperc és ezredmásodperc által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| hour | int | A **day** órája, amelyet a létrehozott példány képvisel. |
| minute | int | A **hour** perce, amelyet a létrehozott példány képvisel. |
| second | int | A **minute** másodperce, amelyet a létrehozott példány képvisel. |
| millisecond | int | A **second** ezredmásodperce, amelyet a létrehozott példány képvisel. |
| kind | [DateTimeKind](../../datetimekind/) | Az az érték, amely azt jelzi, hogy a megadott dátum- és időparaméterek helyi időt, UTC-t vagy egyikiket sem határoznak meg. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) konstruktor


Létrehoz egy példányt, amely a megadott naptárban egy adott év, hónap, nap, óra, perc, másodperc és ezredmásodperc által meghatározott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| year | int | Az év, amelyet a létrehozott példány képvisel. |
| month | int | A **year** hónapja, amelyet a létrehozott példány képvisel. |
| day | int | A **month** napja, amelyet a létrehozott példány képvisel. |
| hour | int | A **day** órája, amelyet a létrehozott példány képvisel. |
| minute | int | A **hour** perce, amelyet a létrehozott példány képvisel. |
| second | int | A **minute** másodperce, amelyet a létrehozott példány képvisel. |
| millisecond | int | A **second** ezredmásodperce, amelyet a létrehozott példány képvisel. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | Az az érték, amely azt jelzi, hogy a megadott dátum- és időparaméterek helyi időt, UTC-t vagy egyikiket sem határoznak meg. |
| calendar | [DateTimeKind](../../datetimekind/) | A naptár, amely a megadott **year**, **month** és **day** értelmezésére szolgál. |

## DateTime::DateTime(int64_t, DateTimeKind) konstruktor


Létrehoz egy példányt, amely egy ticks számként megadott dátum- és időértéket képvisel.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ticks | **int64_t** | A 100 ns-es intervallumok száma, amely eltelt 0001. január 1. 00:00:00.000 óta a georgiai naptárban. |
| kind | [DateTimeKind](../../datetimekind/) | Az az érték, amely azt jelzi, hogy a **ticks** paraméter helyi időt, UTC-t vagy egyikiket sem határoz meg. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) konstruktor


Létrehoz egy példányt, amely egy ticks számként megadott dátum- és időértéket képvisel. INTERNAL USE-RA.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ticks | **int64_t** | A 100 ns-es intervallumok száma, amely eltelt 0001. január 1. 00:00:00.000 óta a georgiai naptárban. |
| kind | [DateTimeKind](../../datetimekind/) | Az az érték, amely azt jelzi, hogy a **ticks** paraméter helyi időt, UTC-t vagy egyikiket sem határoz meg. |
| is_ambiguous_local_dst | **bool** | Igaz, ha a megadott dátum és idő kettős értelmű, és több UTC időponthoz is hozzárendelhető. |

## DateTime::DateTime(const DateTime\&) konstruktor


Másoló konstruktorral hoz létre egy példányt.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dt | const [DateTime](../)\& | Egy [DateTime](../) osztály példánya, amelyből a képviselt dátum- és időértéket másolni kell |

## Lásd még

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)