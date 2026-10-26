---
title: WriteAsync()
second_title: Riferimento API Aspose.Slides per C++
description: Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente all'interno di questo stream del numero di byte scritti e monitora le richieste di annullamento.
type: docs
weight: 261
url: /it/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente all'interno di questo stream del numero di byte scritti e monitora le richieste di annullamento.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array che contiene i byte da scrivere. |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia il sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di annullamento. |

### Return Value

Un'operazione (task) che rappresenta l'operazione di scrittura asincrona.

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)