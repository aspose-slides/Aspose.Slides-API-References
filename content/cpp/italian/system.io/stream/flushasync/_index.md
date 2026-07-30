---
title: FlushAsync()
second_title: Riferimento API di Aspose.Slides per C++
description: Cancella in modo asincrono tutti i buffer di questo stream, provoca la scrittura di eventuali dati bufferizzati sul dispositivo sottostante e monitora le richieste di annullamento.
type: docs
weight: 118
url: /it/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metodo

Cancella in modo asincrono tutti i buffer di questo stream, provoca la scrittura di eventuali dati bufferizzati sul dispositivo sottostante e monitora le richieste di annullamento.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di annullamento. |

### Valore di ritorno

Un’attività che rappresenta l’operazione di flush asincrona.

## Stream::FlushAsync() metodo

Cancella in modo asincrono tutti i buffer di questo stream, provoca la scrittura di eventuali dati bufferizzati sul dispositivo sottostante e monitora le richieste di annullamento.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Valore di ritorno

Un’attività che rappresenta l’operazione di flush asincrona.

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)