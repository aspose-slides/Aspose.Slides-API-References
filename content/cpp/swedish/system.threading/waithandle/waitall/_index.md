---
title: WaitAll()
second_title: Aspose.Slides för C++ API-referens
description: Väntar på att alla handtag ska avfyras.
type: docs
weight: 1
url: /sv/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metod


Väntar på att alla handtag ska avfyras.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll-och-återvänd, positiva värden är tidsgränser. |

### Returvärde

Sant om alla handtag har avfyrats, falskt om tidsgränsen överskreds.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metod


Väntar på att alla handtag ska avfyras.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |
| timeout | [TimeSpan](../../../system/timespan/) | En [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller en [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta oändligt. |

### Returvärde

Sant om alla handtag har avfyrats, falskt om tidsgränsen överskreds.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metod


Väntar på att alla handtag ska avfyras.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |

### Returvärde

Sant när varje element i waitHandles har mottagit en signal; annars returnerar metoden aldrig.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [WaitHandle](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Library [Aspose.Slides](../../../)