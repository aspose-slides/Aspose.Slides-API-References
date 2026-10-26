---
title: get_Current()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el contexto de sincronización para el hilo actual.
type: docs
weight: 40
url: /es/system.threading/synchronizationcontext/get_current/
---
## Método SynchronizationContext::get_Current()

Obtiene el contexto de sincronización para el hilo actual.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### Valor devuelto

SharedPtr<SynchronizationContext> Un puntero compartido al contexto de sincronización del hilo actual.

## Comentarios

Devuelve null si no se ha establecido ningún contexto de sincronización para el hilo actual.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)