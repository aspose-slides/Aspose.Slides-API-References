---
title: QueueUserWorkItem()
second_title: Aspose.Slides per C++ Riferimento API
description: Inserisce l'elemento di lavoro nella coda con un callback senza parametri.
type: docs
weight: 14
url: /it/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) metodo

Inserisce l'elemento di lavoro nella coda con un callback senza parametri.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |

### Valore di ritorno

Restituisce sempre true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) metodo

Inserisce l'elemento di lavoro nella coda con un callback senza parametri.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Callback function to be used as a job. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Job function parameter. |

### Valore di ritorno

Restituisce sempre true.

## Vedi anche

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ThreadPool](../)
* Classe [Object](../../../system/object/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)