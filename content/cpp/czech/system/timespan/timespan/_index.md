---
title: TimeSpan()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytváří objekt TimeSpan, který představuje nulový časový interval.
type: docs
weight: 1
url: /cs/system/timespan/timespan/
---
## TimeSpan::TimeSpan() konstruktor


Vytváří objekt [TimeSpan](../) představující nulový časový interval.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) konstruktor


Vytváří instanci třídy [TimeSpan](../) představující zadaný časový interval.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ticks | **int64_t** | Časový interval, který má být reprezentován konstruovanou instancí, vyjádřený jako počet intervalů po 100 nanosekund. |

## TimeSpan::TimeSpan(int, int, int) konstruktor


Vytváří instanci třídy [TimeSpan](../) představující časový interval, který je roven součtu zadaného počtu hodin, minut a sekund.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hours | int | Počet hodin v hodinové složce časového intervalu, který má být reprezentován konstruovanou instancí |
| minutes | int | Počet minut v minutové složce časového intervalu, který má být reprezentován konstruovanou instancí |
| seconds | int | Počet sekund ve sekundové složce časového intervalu, který má být reprezentován konstruovanou instancí |

## TimeSpan::TimeSpan(int, int, int, int, int) konstruktor


Vytváří instanci třídy [TimeSpan](../) představující časový interval, který je roven součtu zadaného počtu hodin, minut, sekund a milisekund.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| days | int | Počet dní v denní složce časového intervalu, který má být reprezentován konstruovanou instancí |
| hours | int | Počet hodin v hodinové složce časového intervalu, který má být reprezentován konstruovanou instancí |
| minutes | int | Počet minut v minutové složce časového intervalu, který má být reprezentován konstruovanou instancí |
| seconds | int | Počet sekund ve sekundové složce časového intervalu, který má být reprezentován konstruovanou instancí |
| milliseconds | int | Počet milisekund v milisekundové složce časového intervalu, který má být reprezentován konstruovanou instancí |

## TimeSpan::TimeSpan(const TimeSpan\&) konstruktor


Vytváří objekt [TimeSpan](../) představující časový interval roven časovému intervalu reprezentovanému zadaným objektem [TimeSpan](../).

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Viz také

* Třída [TimeSpan](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)