---
title: QueueUserWorkItem()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge l'unità di lavoro alla coda.
type: docs
weight: 1
url: /it/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metodo

Aggiunge un'unità di lavoro alla coda.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Funzione di callback da eseguire. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argomento della funzione di callback. |

### Valore restituito

Restituisce sempre true.

## Vedi anche

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ThreadPoolImpl](../)
* Spazio dei nomi [System::Threading](../../)
* Library [Aspose.Slides](../../../)