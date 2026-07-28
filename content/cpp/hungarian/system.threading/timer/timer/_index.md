---
title: Timer()
second_title: Aspose.Slides C++ API referenciája
description: Konstruktor.
type: docs
weight: 1
url: /hu/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | A timer által meghívandó függvény. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | A timer által meghívandó függvény. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | A visszahívási függvény argumentuma. |
| dueTime | **int64_t** | [Timeout](../../timeout/) az első visszahívási függvény meghívása előtt, ezredmásodpercben; a negatív értékek nem ütemezik a timert a létrehozás után, így később újraütemezhető. |
| period | **int64_t** | [Timeout](../../timeout/) a következő visszahívási függvény meghívások között, ezredmásodpercben; a nem pozitív értékek azt jelentik, hogy a timert csak egyszer kell végrehajtani. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | A timer által meghívandó függvény. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | A visszahívási függvény argumentuma. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) az első visszahívási függvény meghívása előtt; a negatív értékek nem ütemezik a timert a létrehozás után, így később újraütemezhető. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) a következő visszahívási függvény meghívások között; a nem pozitív értékek azt jelentik, hogy a timert csak egyszer kell végrehajtani. |

## Lásd még

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Timer](../)
* Osztály [Object](../../../system/object/)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtere [System::Threading](../../)
* Library [Aspose.Slides](../../../)