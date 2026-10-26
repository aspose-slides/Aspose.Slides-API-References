---
title: SetSynchronizationContext()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el contexto de sincronización para el hilo actual.
type: docs
weight: 53
url: /es/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) método

Establece el contexto de sincronización para el subproceso actual.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | El contexto de sincronización que se establecerá para el subproceso actual. |

## Comentarios

Pasar nullptr borrará el contexto de sincronización para el subproceso actual. 

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)