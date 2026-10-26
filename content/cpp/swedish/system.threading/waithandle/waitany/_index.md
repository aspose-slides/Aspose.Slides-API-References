---
title: WaitAny()
second_title: Aspose.Slides för C++ API-referens
description: Väntar på att något av handtagen ska avfyras.
type: docs
weight: 14
url: /sv/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metod


Väntar på att någon av handtagen ska avfyras.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll-och-retur, positiva värden är tidsgränser. |

### Returvärde

True om någon handtag avfyrdes, false om tidsgränsen överskreds.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metod


Väntar på att någon av handtagen ska avfyras.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |
| timeout | [TimeSpan](../../../system/timespan/) | En [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller en [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta obegränsat. |

### Returvärde

True om någon handtag avfyrdes, false om tidsgränsen överskreds.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metod


Väntar på att någon av handtagen ska avfyras.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handtag att vänta på. |

### Returvärde

True när varje element i waitHandles har mottagit en signal; annars returnerar metoden aldrig.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [WaitHandle](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)