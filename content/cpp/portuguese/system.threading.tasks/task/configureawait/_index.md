---
title: ConfigureAwait()
second_title: Referência da API Aspose.Slides for C++
description: Configura como as esperas nesta tarefa devem se comportar em relação à captura de contexto.
type: docs
weight: 144
url: /pt/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const método

Configura como as esperas nesta tarefa devem se comportar em relação à captura de contexto.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indica se deve continuar no contexto capturado |

### Valor de Retorno

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Um awaitable configurado

## Veja Também

* Classe [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Classe [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)