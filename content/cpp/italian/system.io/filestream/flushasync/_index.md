---
title: FlushAsync()
second_title: Riferimento API Aspose.Slides per C++
description: Cancella in modo asincrono tutti i buffer di questo flusso, provoca la scrittura di eventuali dati bufferizzati sul dispositivo sottostante e monitora le richieste di annullamento.
type: docs
weight: 157
url: /it/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metodo

Cancella in modo asincrono tutti i buffer per questo flusso, provoca la scrittura di eventuali dati bufferizzati sul dispositivo sottostante e monitora le richieste di annullamento.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di annullamento. |

### Valore di ritorno

Un'attività che rappresenta l'operazione di flush asincrona.

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)