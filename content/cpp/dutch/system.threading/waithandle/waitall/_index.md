---
title: WaitAll()
second_title: Aspose.Slides for C++ API Referentie
description: Wacht tot alle handles worden geactiveerd.
type: docs
weight: 1
url: /nl/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) methode


Wacht tot alle handles worden geactiveerd.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles om op te wachten. |
| millisecondsTimeout | int | [Timeout](../../timeout/) om te wachten, in milliseconden; -1 betekent oneindig wachten, 0 betekent controle en direct terugkeren, positieve waarden zijn time-outs. |

### Retourwaarde

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) methode


Wacht tot alle handles worden geactiveerd.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles om op te wachten. |
| timeout | [TimeSpan](../../../system/timespan/) | Een [System::TimeSpan](../../../system/timespan/) die het aantal milliseconden voor wachten weergeeft, of een [System::TimeSpan](../../../system/timespan/) die -1 milliseconden voor onbeperkt wachten weergeeft. |

### Retourwaarde

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) methode


Wacht tot alle handles worden geactiveerd.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles om op te wachten. |

### Retourwaarde

True when every element in waitHandles has received a signal; otherwise the method never returns.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [WaitHandle](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Library [Aspose.Slides](../../../)