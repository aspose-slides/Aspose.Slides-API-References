---
title: ConfigureAwait()
second_title: Referencia de la API de Aspose.Slides para C++
description: Configura cómo deben comportarse los await en esta tarea respecto a la captura del contexto.
type: docs
weight: 144
url: /es/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const método


Configura cómo deben comportarse los await en esta tarea respecto a la captura del contexto.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indica si debe continuar en el contexto capturado |

### Valor de retorno

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Un awaitable configurado

## Ver también

* Clase [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Clase [Task](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)