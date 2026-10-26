---
title: ConfigureAwait()
second_title: Riferimento API di Aspose.Slides per C++
description: Configura un awaiter per questa attività.
type: docs
weight: 92
url: /it/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const metodo

Configura un awaiter per questa attività.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true per tentare di delegare la continuazione al contesto originale catturato; altrimenti, false. |

### Valore di ritorno

ConfiguredResultValueTaskAwaitable<T> Un oggetto che configura come si comportano gli awaiter per questa attività.

## Vedi anche

* Classe [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Classe [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)