---
title: WaitAny()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot een van de handles wordt geactiveerd.
type: docs
weight: 14
url: /nl/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Wacht tot een van de handles wordt geactiveerd.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handvatten om op te wachten. |
| millisecondsTimeout | int | [Timeout](../../timeout/) om te wachten, in milliseconden; -1 betekent oneindig wachten, 0 betekent controle-en-terugkeer, positieve waarden zijn time-outs. |

### Retourwaarde

True if any handle fired, false if timeout exceeded.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Wacht tot een van de handles wordt geactiveerd.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handvatten om op te wachten. |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) dat het aantal milliseconden aangeeft dat gewacht moet worden, of een [System::TimeSpan](../../../system/timespan/) dat -1 milliseconden aangeeft voor onbeperkt wachten. |

### Retourwaarde

True if any handle fired, false if timeout exceeded.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Wacht tot een van de handles wordt geactiveerd.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handvatten om op te wachten. |

### Retourwaarde

True wanneer elk element in waitHandles een signaal heeft ontvangen; anders keert de methode nooit terug.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [WaitHandle](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)