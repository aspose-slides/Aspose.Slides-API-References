---
title: operator-()
second_title: Aspose.Slides for C++ API hivatkozás
description: Új példányt ad vissza a DateTimeOffset osztályból, amely a dátum- és időértéket képviseli, amely a megadott időintervallum kivonásának eredménye a jelenlegi objektum által képviselt értékből.
type: docs
weight: 521
url: /hu/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const metódus


Új [DateTimeOffset](../) osztálypéldányt ad vissza, amely a dátum- és időértéket képviseli, ami a megadott időintervallum kivonásának eredménye a jelenlegi objektum által képviselt értékből.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Az eltávolítandó időintervallum |

### Visszatérési érték

Új [DateTimeOffset](../) osztálypéldány, amely a dátum- és időértéket képviseli, ami a **value** kivonásának eredménye a jelenlegi objektum által képviselt értékből.

## DateTimeOffset::operator-(const DateTimeOffset&) const metódus


[TimeSpan](../../timespan/) osztály egy példányát adja vissza, amely a jelenlegi és a megadott objektumok által képviselt dátum- és időértékek közötti időintervallumot jelöli.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Egy [DateTime](../../datetime/) osztály példánya, amely az intervallum egyik végét jelöli |

### Visszatérési érték

[TimeSpan](../../timespan/) osztály egy példánya, amely a jelenlegi objektum és **other** által képviselt dátum- és időértékek közötti időintervallumot jelöli.

## Lásd még

* Osztály [DateTimeOffset](../)
* Osztály [TimeSpan](../../timespan/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)