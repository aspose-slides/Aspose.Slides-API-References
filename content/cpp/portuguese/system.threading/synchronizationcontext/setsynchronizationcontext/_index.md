---
title: SetSynchronizationContext()
second_title: Referência da API Aspose.Slides para C++
description: Define o contexto de sincronização para a thread atual.
type: docs
weight: 53
url: /pt/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) método

Define o contexto de sincronização para a thread atual.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | O contexto de sincronização a ser definido para a thread atual. |

## Observações

Passar nullptr limpará o contexto de sincronização da thread atual. 

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)