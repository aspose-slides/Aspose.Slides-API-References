---
title: TimeSpan()
second_title: Aspose.Slides dla C++ – odwołanie do API
description: Tworzy obiekt TimeSpan, który reprezentuje zerowy przedział czasu.
type: docs
weight: 1
url: /pl/system/timespan/timespan/
---
## TimeSpan::TimeSpan() konstruktor


Tworzy obiekt [TimeSpan](../) reprezentujący zerowy przedział czasu.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) konstruktor


Tworzy instancję klasy [TimeSpan](../), reprezentującą określony przedział czasu.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ticks | **int64_t** | Przedział czasu, który ma zostać reprezentowany przez tworzoną instancję, wyrażony jako liczba interwałów 100-nanosekundowych. |

## TimeSpan::TimeSpan(int, int, int) konstruktor


Tworzy instancję klasy [TimeSpan](../), reprezentującą przedział czasu równy sumie określonej liczby godzin, minut i sekund.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hours | int | Liczba godzin w komponencie godzin przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| minutes | int | Liczba minut w komponencie minut przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| seconds | int | Liczba sekund w komponencie sekund przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |

## TimeSpan::TimeSpan(int, int, int, int, int) konstruktor


Tworzy instancję klasy [TimeSpan](../), reprezentującą przedział czasu równy sumie określonej liczby dni, godzin, minut, sekund i milisekund.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| days | int | Liczba dni w komponencie dni przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| hours | int | Liczba godzin w komponencie godzin przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| minutes | int | Liczba minut w komponencie minut przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| seconds | int | Liczba sekund w komponencie sekund przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |
| milliseconds | int | Liczba milisekund w komponencie milisekund przedziału czasu, który ma zostać reprezentowany przez tworzoną instancję |

## TimeSpan::TimeSpan(const TimeSpan\&) konstruktor


Tworzy obiekt [TimeSpan](../) reprezentujący przedział czasu równy przedziałowi czasu reprezentowanemu przez określony obiekt [TimeSpan](../).

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Zobacz także

* Klasa [TimeSpan](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)