---
title: WriteAsync()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente all'interno di questo stream del numero di byte scritti e monitora le richieste di cancellazione.
type: docs
weight: 66
url: /it/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metodo

Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente all'interno di questo stream del numero di byte scritti e monitora le richieste di cancellazione.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere. |
| offset | **int32_t** | Un indice basato su zero dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Il token da monitorare per le richieste di cancellazione. |

### Valore di ritorno

Un task che rappresenta l'operazione di scrittura asincrona.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive in modo asincrono una sequenza di byte nello stream corrente, avanza la posizione corrente all'interno di questo stream del numero di byte scritti e monitora le richieste di cancellazione.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere. |
| offset | **int32_t** | Un indice basato su zero dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere. |

### Valore di ritorno

Un task che rappresenta l'operazione di scrittura asincrona.

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)