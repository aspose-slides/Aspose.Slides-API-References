---
title: QueueUserWorkItem()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Arbeitselement zur Warteschlange hinzu.
type: docs
weight: 1
url: /de/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) Methode


Fügt ein Arbeitselement zur Warteschlange hinzu.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-Funktion, die ausgeführt werden soll. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument der Callback-Funktion. |

### Rückgabewert

Gibt immer true zurück.

## Siehe auch

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ThreadPoolImpl](../)
* Namensraum [System::Threading](../../)
* Library [Aspose.Slides](../../../)