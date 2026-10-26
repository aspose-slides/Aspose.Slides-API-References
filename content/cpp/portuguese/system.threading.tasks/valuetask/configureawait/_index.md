---
title: ConfigureAwait()
second_title: Referência da API Aspose.Slides para C++
description: Configura um awaiter para esta tarefa.
type: docs
weight: 79
url: /pt/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const method


Configura um awaiter para esta tarefa.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true para tentar encaminhar a continuação de volta ao contexto original capturado; caso contrário, false. |

### Valor de Retorno

ConfiguredValueTaskAwaitable Um objeto que configura como os awaiters se comportam para esta tarefa.

## Veja Também

* Class [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)