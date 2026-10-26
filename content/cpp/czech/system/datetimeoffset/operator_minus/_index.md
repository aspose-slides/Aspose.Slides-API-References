---
title: operator-()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací novou instanci třídy DateTimeOffset představující datum a čas, což je výsledek odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.
type: docs
weight: 521
url: /cs/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const method

Vrací novou instanci třídy [DateTimeOffset](../) představující datum a čas, což je výsledek odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Časový interval, který se má odečíst |

### Návratová hodnota

Nová instance třídy [DateTimeOffset](../) představující datum a čas, což je výsledek odečtení **value** od hodnoty reprezentované aktuálním objektem.

## DateTimeOffset::operator-(const DateTimeOffset\&) const method

Vrací instanci třídy [TimeSpan](../../timespan/), která představuje časový interval mezi hodnotami data a času reprezentovanými aktuálním a zadaným objektem.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Instance třídy [DateTime](../../datetime/) označující jeden konec intervalu, který se má vypočítat |

### Návratová hodnota

Instance třídy [TimeSpan](../../timespan/) představující časový interval mezi hodnotami data a času reprezentovanými aktuálním objektem a **other**.

## Viz také

* Třída [DateTimeOffset](../)
* Třída [TimeSpan](../../timespan/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)