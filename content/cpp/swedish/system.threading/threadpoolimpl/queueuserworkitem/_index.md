---
title: QueueUserWorkItem()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till arbetsobjekt i kön.
type: docs
weight: 1
url: /sv/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metod

Lägger till arbetsobjekt i kön.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-funktion att köra. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Callback-funktionens argument. |

### Returvärde

Returnerar alltid true.

## Se även

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [ThreadPoolImpl](../)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)