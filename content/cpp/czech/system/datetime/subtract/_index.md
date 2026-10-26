---
title: Subtract()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací novou instanci třídy DateTime představující hodnotu data a času, která je výsledkem odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.
type: docs
weight: 326
url: /cs/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metoda

Vrací novou instanci třídy [DateTime](../), která představuje hodnotu data a času, jež je výsledkem odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Časový interval k odečtení |

### Návratová hodnota

Nová instance třídy [DateTime](../) představující hodnotu data a času, která je výsledkem odečtení **duration** od hodnoty reprezentované aktuálním objektem.

## DateTime::Subtract(DateTime) const metoda

Vrací instanci třídy [TimeSpan](../../timespan/) představující časový interval mezi hodnotami data a času reprezentovanými aktuálním a zadaným objektem.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [DateTime](../) | Instanci třídy [DateTime](../) představující jeden konec intervalu, který se má vypočítat |

### Návratová hodnota

Instanci třídy [TimeSpan](../../timespan/) představující časový interval mezi hodnotami data a času reprezentovanými aktuálním objektem a **value**.

## Viz také

* Třída [DateTime](../)
* Třída [TimeSpan](../../timespan/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)