---
title: ConfigureAwait()
second_title: Referencia de la API de Aspose.Slides para C++
description: Configura un awaiter para esta tarea.
type: docs
weight: 92
url: /es/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const método

Configura un awaiter para esta tarea.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true para intentar reactivar la continuación en el contexto original capturado; de lo contrario, false. |

### Valor devuelto

ConfiguredResultValueTaskAwaitable<T> Un objeto que configura cómo se comportan los awaiters para esta tarea.

## Ver también

* Clase [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Clase [ResultValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)