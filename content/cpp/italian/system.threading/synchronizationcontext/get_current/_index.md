---
title: get_Current()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il contesto di sincronizzazione per il thread corrente.
type: docs
weight: 40
url: /it/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() metodo

Restituisce il contesto di sincronizzazione per il thread corrente.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### Valore restituito

SharedPtr<SynchronizationContext> Un puntatore condiviso al contesto di sincronizzazione del thread corrente.
## Osservazioni


Restituisce null se non è stato impostato alcun contesto di sincronizzazione per il thread corrente. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SynchronizationContext](../)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)