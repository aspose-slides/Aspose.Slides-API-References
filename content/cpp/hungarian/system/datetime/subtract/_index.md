---
title: Subtract()
second_title: Aspose.Slides C++ API referencia
description: Egy új DateTime osztálypéldányt ad vissza, amely a dátum és idő értéket képviseli, ami a megadott időtartam kivonásának eredménye az aktuális objektum által képviselt értékből.
type: docs
weight: 326
url: /hu/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metódus


Visszaad egy új [DateTime](../) osztálypéldányt, amely a dátum és idő értéket képviseli, amely a megadott időtartam kivonásának eredménye az aktuális objektum által képviselt értékből.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Egy időintervallum, amelyet le kell vonni |

### Visszatérési érték

Egy új [DateTime](../) osztálypéldány, amely a dátum és idő értéket képviseli, amely a **duration** kivonásának eredménye az aktuális objektum által képviselt értékből.

## DateTime::Subtract(DateTime) const metódus


Visszaad egy [TimeSpan](../../timespan/) osztálypéldányt, amely a dátum és idő értékek közötti időintervallumot képviseli, amelyet az aktuális és a megadott objektumok reprezentálnak.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [DateTime](../) | Egy [DateTime](../) osztálypéldány, amely az intervallum egyik végét jelöli, amelyet ki kell számítani |

### Visszatérési érték

Egy [TimeSpan](../../timespan/) osztálypéldány, amely a dátum és idő értékek közötti időintervallumot képviseli, amelyet az aktuális objektum és a **value** reprezentálnak.

## Lásd még

* Osztály [DateTime](../)
* Osztály [TimeSpan](../../timespan/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)