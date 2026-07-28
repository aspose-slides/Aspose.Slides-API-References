---
title: QueueUserWorkItem()
second_title: Aspose.Slides C++ API-referencia
description: Munkaelemet ad a sorhoz.
type: docs
weight: 1
url: /hu/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metódus

Munkatételt ad a sorhoz.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Végrehajtandó visszahívási függvény. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Visszahívási függvény argumentuma. |

### Visszatérési érték

Mindig true értéket ad vissza.

## Lásd még

* Típusdefiníció [WaitCallback](../../waitcallback/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [ThreadPoolImpl](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)