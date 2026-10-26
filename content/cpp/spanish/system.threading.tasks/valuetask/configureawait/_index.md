---
title: ConfigureAwait()
second_title: Referencia de API de Aspose.Slides para C++
description: Configura un awaiter para esta tarea.
type: docs
weight: 79
url: /es/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const método

Configura un awaiter para esta tarea.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true para intentar volver a canalizar la continuación al contexto original capturado; de lo contrario, false. |

### Valor devuelto

ConfiguredValueTaskAwaitable Un objeto que configura cómo se comportan los awaiters para esta tarea.

## Ver también

* Clase [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Clase [ValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)