---
title: ReadAsync()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge in modo asincrono una sequenza di byte dal flusso corrente, avanza la posizione nel flusso del numero di byte letti e monitora le richieste di cancellazione.
type: docs
weight: 40
url: /it/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metodo

Legge in modo asincrono una sequenza di byte dal flusso corrente, avanza la posizione nel flusso del numero di byte letti e controlla le richieste di cancellazione.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti. |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare la scrittura. |
| count | **int32_t** | Il numero di byte da leggere. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di cancellazione. |

### Valore di ritorno

Un'attività che rappresenta l'operazione di lettura asincrona. Il valore del parametro TResult contiene il numero totale di byte letti nel buffer. Il valore restituito può essere inferiore al numero di byte richiesti se il numero di byte attualmente disponibili è inferiore a quello richiesto, oppure può essere 0 (zero) se è stato raggiunto la fine del flusso.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Legge in modo asincrono una sequenza di byte dal flusso corrente, avanza la posizione nel flusso del numero di byte letti e controlla le richieste di cancellazione.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti. |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare la scrittura. |
| count | **int32_t** | Il numero di byte da leggere. |

### Valore di ritorno

Un'attività che rappresenta l'operazione di lettura asincrona. Il valore del parametro TResult contiene il numero totale di byte letti nel buffer. Il valore restituito può essere inferiore al numero di byte richiesti se il numero di byte attualmente disponibili è inferiore a quello richiesto, oppure può essere 0 (zero) se è stato raggiunto la fine del flusso.

## Vedi anche

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)