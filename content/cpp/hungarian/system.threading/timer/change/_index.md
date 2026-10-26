---
title: Change()
second_title: Aspose.Slides C++ API referencia
description: Újraütemezi vagy törli az időzítőt.
type: docs
weight: 14
url: /hu/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metódus

Újraütemezi vagy törli az időzítőt.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) a következő visszahívási függvény meghívása előtt, ezredmásodpercben; a negatív értékek törlik az időzítőt még akkor is, ha az már ütemezve volt. |
| period | **int64_t** | [Timeout](../../timeout/) a következő visszahívási függvények közötti időközben, ezredmásodpercben; a nem pozitív értékek azt jelentik, hogy az időzítőt csak egyszer kell végrehajtani. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metódus

Újraütemezi vagy törli az időzítőt.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) a következő visszahívási függvény meghívása előtt; a negatív értékek törlik az időzítőt még akkor is, ha az már ütemezve volt. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) a következő visszahívási függvények közötti időközben; a nem pozitív értékek azt jelentik, hogy az időzítőt csak egyszer kell végrehajtani. |

## Lásd még

* Osztály [Timer](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)