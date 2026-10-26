---
title: QueueUserWorkItem()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een werkitem toe aan de wachtrij.
type: docs
weight: 1
url: /nl/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) methode

Voegt een werkitem toe aan de wachtrij.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback-functie die moet worden uitgevoerd. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument van de callback-functie. |

### Retourwaarde

Geeft altijd true terug.

## Zie ook

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ThreadPoolImpl](../)
* Naamruimte [System::Threading](../../)
* Library [Aspose.Slides](../../../)