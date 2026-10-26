---
title: ConfigureAwait()
second_title: Riferimento API Aspose.Slides per C++
description: Configura il modo in cui le attese su questo task dovrebbero comportarsi riguardo alla cattura del contesto.
type: docs
weight: 144
url: /it/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const metodo

Configura il modo in cui le attese su questo task dovrebbero comportarsi riguardo alla cattura del contesto.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indica se continuare sul contesto catturato |

### Valore di ritorno

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Un awaitable configurato

## Vedi anche

* Classe [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Classe [Task](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)