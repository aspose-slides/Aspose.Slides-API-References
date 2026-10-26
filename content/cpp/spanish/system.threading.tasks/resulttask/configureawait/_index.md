---
title: ConfigureAwait()
second_title: Referencia de API de Aspose.Slides para C++
description: Configura cómo deben comportarse los await en esta tarea de resultado respecto a la captura del contexto.
type: docs
weight: 27
url: /es/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const método

Configura cómo deben comportarse los await en esta tarea de resultado respecto a la captura del contexto.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Si debe continuar en el contexto capturado |

### Valor de retorno

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Un awaitable configurado para el resultado
## Observaciones

Esto permite un control granular del flujo de contexto para los patrones async/await.

## Ver también

* Clase [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Clase [ResultTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)