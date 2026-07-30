---
title: WaitAll()
second_title: Riferimento API Aspose.Slides per C++
description: Attende che tutti gli handle vengano attivati.
type: docs
weight: 1
url: /it/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metodo


Attende che tutti gli handle vengano attivati.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |
| millisecondsTimeout | int | [Timeout](../../timeout/) da attendere, in millisecondi; -1 significa attesa infinita, 0 significa controllo e ritorno, i valori positivi sono timeout. |

### Valore di ritorno

True se tutti gli handle sono stati attivati, false se è stato superato il timeout.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metodo


Attende che tutti gli handle vengano attivati.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) che rappresenta il numero di millisecondi da attendere, o un [System::TimeSpan](../../../system/timespan/) che rappresenta -1 millisecondi per attendere indefinitamente. |

### Valore di ritorno

True se tutti gli handle sono stati attivati, false se è stato superato il timeout.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metodo


Attende che tutti gli handle vengano attivati.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handle da attendere. |

### Valore di ritorno

True quando ogni elemento in waitHandles ha ricevuto un segnale; altrimenti il metodo non ritorna mai.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)