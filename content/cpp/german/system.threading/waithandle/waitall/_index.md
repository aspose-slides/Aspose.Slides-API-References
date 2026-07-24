---
title: WaitAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis alle Handles ausgelöst werden.
type: docs
weight: 1
url: /de/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) Methode


Wartet, bis alle Handles ausgelöst werden.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles, auf die gewartet wird. |
| millisecondsTimeout | int | [Timeout](../../timeout/) zum Warten, in Millisekunden; -1 bedeutet unbegrenztes Warten, 0 bedeutet prüfen und zurückkehren, positive Werte sind Zeitlimits. |

### Rückgabewert

True, wenn alle Handles ausgelöst wurden, false, wenn das Zeitlimit überschritten wurde.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) Methode


Wartet, bis alle Handles ausgelöst werden.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles, auf die gewartet wird. |
| timeout | [TimeSpan](../../../system/timespan/) | Ein [System::TimeSpan](../../../system/timespan/), das die Anzahl der Millisekunden zum Warten darstellt, oder ein [System::TimeSpan](../../../system/timespan/), das -1 Millisekunden für unbegrenztes Warten darstellt. |

### Rückgabewert

True, wenn alle Handles ausgelöst wurden, false, wenn das Zeitlimit überschritten wurde.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) Methode


Wartet, bis alle Handles ausgelöst werden.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles, auf die gewartet wird. |

### Rückgabewert

True, wenn jedes Element in waitHandles ein Signal erhalten hat; andernfalls kehrt die Methode nie zurück.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [WaitHandle](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)