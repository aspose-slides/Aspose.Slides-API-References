---
title: operator-()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací novou instanci třídy DateTime představující datum a čas, který je výsledkem odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.
type: docs
weight: 651
url: /cs/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metoda


Vrací novou instanci třídy [DateTime](../) představující datum a čas, který je výsledkem odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Časový interval k odečtení |

### Návratová hodnota

Nová instance třídy [DateTime](../) představující datum a čas, který je výsledkem odečtení **value** od hodnoty reprezentované aktuálním objektem.

## DateTime::operator-(DateTime) const metoda


Vrací instanci třídy [TimeSpan](../../timespan/) představující časový interval mezi datumy a časy reprezentovanými aktuálním a zadaným objektem.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [DateTime](../) | Instance třídy [DateTime](../) označující jeden konec intervalu, který má být vypočítán |

### Návratová hodnota

Instance třídy [TimeSpan](../../timespan/) představující časový interval mezi datumy a časy reprezentovanými aktuálním objektem a **value**.

## Viz také

* Třída [DateTime](../)
* Třída [TimeSpan](../../timespan/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)