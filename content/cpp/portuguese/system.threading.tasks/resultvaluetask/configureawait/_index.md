---
title: ConfigureAwait()
second_title: Referência da API Aspose.Slides para C++
description: Configura um awaiter para esta tarefa.
type: docs
weight: 92
url: /pt/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const método


Configura um awaiter para esta tarefa.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true para tentar encaminhar a continuação de volta ao contexto original capturado; caso contrário, false. |

### Valor de Retorno

ConfiguredResultValueTaskAwaitable<T> Um objeto que configura como os awaiters se comportam para esta tarefa.

## Veja Também

* Classe [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Classe [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)