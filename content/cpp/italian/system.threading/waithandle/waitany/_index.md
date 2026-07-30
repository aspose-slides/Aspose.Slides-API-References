---
title: WaitAny()
second_title: Riferimento API Aspose.Slides per C++
description: Attende che uno qualsiasi dei handle venga attivato.
type: docs
weight: 14
url: /it/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metodo

Attende che uno qualsiasi dei handle venga attivato.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |
| millisecondsTimeout | int | [Timeout](../../timeout/) da attendere, in millisecondi; -1 indica attesa infinita, 0 indica controllo e ritorno, i valori positivi sono timeout. |

### Valore di Ritorno

True se qualche handle è stato attivato, false se il timeout è stato superato.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metodo

Attende che uno qualsiasi dei handle venga attivato.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) che rappresenta il numero di millisecondi da attendere, oppure un [System::TimeSpan](../../../system/timespan/) che rappresenta -1 millisecondi per attendere indefinitamente. |

### Valore di Ritorno

True se qualche handle è stato attivato, false se il timeout è stato superato.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metodo

Attende che uno qualsiasi dei handle venga attivato.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |

### Valore di Ritorno

True quando ogni elemento in waitHandles ha ricevuto un segnale; altrimenti il metodo non ritorna mai.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)