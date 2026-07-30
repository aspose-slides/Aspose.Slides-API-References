---
title: QueueUserWorkItem()
second_title: Aspose.Slides pro referenci API C++
description: Přidá položku práce do fronty.
type: docs
weight: 1
url: /cs/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metoda


Přidá položku práce do fronty.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funkce zpětného volání k vykonání. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkce zpětného volání. |

### Návratová hodnota

Vždy vrací true.

## Viz také

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Object](../../../system/object/)
* třída [ThreadPoolImpl](../)
* jmenný prostor [System::Threading](../../)
* Library [Aspose.Slides](../../../)