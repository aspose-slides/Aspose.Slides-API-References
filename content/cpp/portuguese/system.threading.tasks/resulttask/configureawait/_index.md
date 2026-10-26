---
title: ConfigureAwait()
second_title: Referência da API Aspose.Slides para C++
description: Configura como as esperas neste resultado de tarefa devem se comportar em relação à captura de contexto.
type: docs
weight: 27
url: /pt/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const método

Configura como as esperas neste resultado de tarefa devem se comportar em relação à captura de contexto.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Se deve continuar no contexto capturado |

### Valor de Retorno

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Um awaitable configurado para o resultado

## Observações

Isso permite controle refinado sobre o fluxo de contexto para padrões async/await

## Veja Também

* Classe [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Classe [ResultTask](../)
* Espaço de nomes [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)