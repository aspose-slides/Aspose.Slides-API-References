---
title: SetSynchronizationContext()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta il contesto di sincronizzazione per il thread corrente.
type: docs
weight: 53
url: /it/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) metodo

Imposta il contesto di sincronizzazione per il thread corrente.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | Il contesto di sincronizzazione da impostare per il thread corrente. |
## Note

Passare nullptr cancellerà il contesto di sincronizzazione per il thread corrente.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [SynchronizationContext](../)
* namespace [System::Threading](../../)
* libreria [Aspose.Slides](../../../)