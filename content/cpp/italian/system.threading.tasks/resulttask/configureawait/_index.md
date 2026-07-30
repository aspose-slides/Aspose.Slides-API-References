---
title: ConfigureAwait()
second_title: Riferimento API di Aspose.Slides per C++
description: Configura come le attese su questo ResultTask devono comportarsi riguardo alla cattura del contesto.
type: docs
weight: 27
url: /it/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const metodo


Configura il modo in cui le attese su questo ResultTask devono comportarsi per quanto riguarda il contesto catturato.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Indica se continuare sul contesto catturato |

### Valore di ritorno

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Un awaitable configurato per il risultato
## Osservazioni



Questo consente un controllo dettagliato del flusso di contesto per i pattern async/await 

## Vedi anche

* Classe [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Classe [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)