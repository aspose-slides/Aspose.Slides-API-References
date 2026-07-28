---
title: WaitAll()
second_title: Aspose.Slides C++ API Referencia
description: Megvárja, hogy az összes kezelő aktiválódjon.
type: docs
weight: 1
url: /hu/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method

Vár az összes kezelő jelzésére.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | A várt kezelők. |
| millisecondsTimeout | int | [Timeout](../../timeout/) a várakozási idő, ezredmásodpercben; -1 jelent végtelen várakozást, 0 jelent ellenőrzés és visszatérés, a pozitív értékek időkorlátok. |

### Visszatérési érték

Igaz, ha minden kezelő jelzett, hamis, ha a időkorlátot túllépték.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method

Vár az összes kezelő jelzésére.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | A várt kezelők. |
| timeout | [TimeSpan](../../../system/timespan/) | Egy [System::TimeSpan](../../../system/timespan/), amely a várandó ezredmásodpercek számát jelenti, vagy egy [System::TimeSpan](../../../system/timespan/), amely -1 ezredmásodpercet jelöl a határtalan várakozáshoz. |

### Visszatérési érték

Igaz, ha minden kezelő jelzett, hamis, ha a időkorlátot túllépték.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method

Vár az összes kezelő jelzésére.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | A várt kezelők. |

### Visszatérési érték

Igaz, ha a waitHandles minden eleme jelzést kap; egyébként a metódus soha nem tér vissza.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [WaitHandle](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Library [Aspose.Slides](../../../)