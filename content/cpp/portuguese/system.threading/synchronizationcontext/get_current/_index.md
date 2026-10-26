---
title: get_Current()
second_title: Aspose.Slides para C++ Referência da API
description: Obtém o contexto de sincronização para a thread atual.
type: docs
weight: 40
url: /pt/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() method


Obtém o contexto de sincronização para a thread atual.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### Valor de retorno

SharedPtr<SynchronizationContext> Um ponteiro compartilhado para o contexto de sincronização da thread atual.
## Observações



Retorna null se nenhum contexto de sincronização tiver sido definido para a thread atual. 

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)