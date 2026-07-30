---
title: ReadAsync()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge in modo asincrono una sequenza di byte dallo stream corrente, avanza la posizione all'interno dello stream del numero di byte letti e monitora le richieste di annullamento.
type: docs
weight: 196
url: /it/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metodo

Legge in modo asincrono una sequenza di byte dallo stream corrente, avanza la posizione all’interno dello stream del numero di byte letti e monitora le richieste di annullamento.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti. |
| offset | **int32_t** | Una posizione indicizzata da zero in **buffer** da cui iniziare la scrittura. |
| count | **int32_t** | Il numero di byte da leggere. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di annullamento. |

### Valore di ritorno

Un'attività che rappresenta l'operazione di lettura asincrona. Il valore del parametro TResult contiene il numero totale di byte letti nel buffer. Il valore restituito può essere inferiore al numero di byte richiesti se il numero di byte attualmente disponibili è inferiore al numero richiesto, oppure può essere 0 (zero) se è stato raggiunto la fine dello stream.

## Vedi anche

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)