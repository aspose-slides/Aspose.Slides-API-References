---
title: ConfigureAwait()
second_title: Riferimento API di Aspose.Slides per C++
description: Configura un awaiter per questo task.
type: docs
weight: 79
url: /it/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const metodo

Configura un awaiter per questo task.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true per tentare di rimandare la continuazione al contesto originale catturato; altrimenti, false. |

### Valore di ritorno

ConfiguredValueTaskAwaitable Un oggetto che configura il comportamento degli awaiter per questo task.

## Vedi anche

* Classe [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Classe [ValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)