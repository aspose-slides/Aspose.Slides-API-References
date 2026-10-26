---
title: TimeSpan()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy TimeSpan objektumot, amely egy nulla időintervallumot reprezentál.
type: docs
weight: 1
url: /hu/system/timespan/timespan/
---
## TimeSpan::TimeSpan() konstruktor


Létrehoz egy [TimeSpan](../) objektumot, amely egy nulla időintervallumot reprezentál.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) konstruktor


Létrehoz egy [TimeSpan](../) osztály példányát, amely a megadott időintervallumot reprezentál.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ticks | **int64_t** | Az időintervallum, amelyet a létrehozott példány reprezentál, 100 nanomásodperces intervallumok számaként kifejezve. |

## TimeSpan::TimeSpan(int, int, int) konstruktor


Létrehoz egy [TimeSpan](../) osztály példányát, amely az adott számú óra, perc és másodperc összegeként definiált időintervallumot reprezentál.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hours | int | Az időintervallum óra komponensében szereplő órák száma, amelyet a példány reprezentál |
| minutes | int | Az időintervallum perc komponensében szereplő percek száma, amelyet a példány reprezentál |
| seconds | int | Az időintervallum másodperc komponensében szereplő másodpercek száma, amelyet a példány reprezentál |

## TimeSpan::TimeSpan(int, int, int, int, int) konstruktor


Létrehoz egy [TimeSpan](../) osztály példányát, amely az adott számú nap, óra, perc, másodperc és ezredmásodperc összegeként definiált időintervallumot reprezentál.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| days | int | Az időintervallum nap komponensében szereplő napok száma, amelyet a példány reprezentál |
| hours | int | Az időintervallum óra komponensében szereplő órák száma, amelyet a példány reprezentál |
| minutes | int | Az időintervallum perc komponensében szereplő percek száma, amelyet a példány reprezentál |
| seconds | int | Az időintervallum másodperc komponensében szereplő másodpercek száma, amelyet a példány reprezentál |
| milliseconds | int | Az időintervallum ezredmásodperc komponensében szereplő ezredmásodpercek száma, amelyet a példány reprezentál |

## TimeSpan::TimeSpan(const TimeSpan\&) konstruktor


Létrehoz egy [TimeSpan](../) objektumot, amely a megadott [TimeSpan](../) objektum által reprezentált időintervallummal egyenlő időintervallumot képvisel.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Lásd még

* Osztály [TimeSpan](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)