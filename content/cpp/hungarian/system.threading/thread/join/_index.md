---
title: Join()
second_title: Aspose.Slides C++ API Referencia
description: Összekapcsolja a kezelt szálat. Korlátlan várakozást hajt végre, ha szükséges.
type: docs
weight: 196
url: /hu/system.threading/thread/join/
---
## Thread::Join() metódus

Összekapcsolja a kezelt szálat. Korlátlan várakozást hajt végre, ha szükséges.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) metódus

Összekapcsolja a kezelt szálat. Korlátolt várakozást hajt végre.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsTimeout | int | Várakozási időkorlát ezredmásodpercben. |

### Visszatérési érték

True, ha a szál sikeresen csatlakozott, false, ha az időkorlát túllépésre került.

## Thread::Join(TimeSpan) metódus

Összekapcsolja a kezelt szálat. Korlátolt várakozást hajt végre.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [TimeSpan](../../../system/timespan/) amely a szál befejezéséhez várandó idő mennyiségét határozza meg. |

### Visszatérési érték

True, ha a szál sikeresen csatlakozott, false, ha az időkorlát túllépésre került.

## Lásd még

* Osztály [Thread](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)