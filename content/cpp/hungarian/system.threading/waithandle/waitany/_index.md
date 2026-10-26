---
title: WaitAny()
second_title: Aspose.Slides C++ API referencia
description: Várakozik, amíg bármelyik kezelő aktiválódik.
type: docs
weight: 14
url: /hu/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metódus


Várakozik, amíg bármelyik kezelő aktiválódik.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Kezelők, amikre várni kell. |
| millisecondsTimeout | int | [Timeout](../../timeout/) várakozási idő, ezredmásodpercben; a -1 végtelen várakozást jelent, a 0 ellenőrzést és visszatérést, a pozitív értékek időkorlátok. |

### Visszatérési érték

Igaz, ha valamelyik kezelő aktiválódott, hamis, ha a timeout lejárt.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metódus


Várakozik, amíg bármelyik kezelő aktiválódik.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Kezelők, amikre várni kell. |
| timeout | [TimeSpan](../../../system/timespan/) | Egy [System::TimeSpan](../../../system/timespan/) amely a várakozandó ezredmásodpercek számát jelenti, vagy egy [System::TimeSpan](../../../system/timespan/) amely -1 ezredmásodpercet jelent a határtalan várakozáshoz. |

### Visszatérési érték

Igaz, ha valamelyik kezelő aktiválódott, hamis, ha a timeout lejárt.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metódus


Várakozik, amíg bármelyik kezelő aktiválódik.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Kezelők, amikre várni kell. |

### Visszatérési érték

Igaz, ha a waitHandles minden eleme jelzést kap; egyébként a metódus soha nem tér vissza.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [WaitHandle](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)