---
title: operator-()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy új DateTime osztály példányt, amely a dátum és idő értéket képviseli, amely a megadott időtartam jelen objektum által reprezentált értékből való kivonás eredménye.
type: docs
weight: 651
url: /hu/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metódus


Visszaad egy új [DateTime](../) osztály példányt, amely a dátum és idő értéket képviseli, ami a megadott időtartam jelen objektum által reprezentált értékből való kivonás eredménye.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | A kivonandó időintervallum |

### Visszatérési érték

Egy új [DateTime](../) osztály példány, amely a dátum és idő értéket jelöli, ami a **value** érték jelen objektum által representált értékből való kivonás eredménye.

## DateTime::operator-(DateTime) const metódus


Visszaad egy [TimeSpan](../../timespan/) osztály példányt, amely a jelen és a megadott objektumok által reprezentált dátum és idő értékek közötti időintervallumot ábrázolja.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [DateTime](../) | Az [DateTime](../) osztály egy példánya, amely az intervallum egyik végpontját jelöli |

### Visszatérési érték

Egy [TimeSpan](../../timespan/) osztály példány, amely a jelen objektum és a **value** által reprezentált dátum és idő értékek közötti időintervallumot ábrázolja.

## Lásd még

* Osztály [DateTime](../)
* Osztály [TimeSpan](../../timespan/)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)