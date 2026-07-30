---
title: WaitOne()
second_title: Riferimento API Aspose.Slides per C++
description: Attende che il gestore venga attivato per un periodo illimitato.
type: docs
weight: 27
url: /it/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metodo


Attende che il gestore venga attivato per un periodo illimitato.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Valore restituito

Restituisce sempre true poiché non si verifica alcun timeout.

## WaitHandle::WaitOne(int) metodo


Attende che il gestore venga attivato.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) da attendere, in millisecondi; -1 significa attesa infinita, 0 significa verifica e ritorno, i valori positivi sono timeout. |

### Valore restituito

True se il gestore è stato attivato, false se il timeout è stato superato.

## WaitHandle::WaitOne(TimeSpan) metodo


Attende che il gestore venga attivato.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) che rappresenta il numero di millisecondi da attendere, o un [System::TimeSpan](../../../system/timespan/) che rappresenta -1 millisecondi per attendere indefinitamente. |

### Valore restituito

True se il gestore è stato attivato, false se il timeout è stato superato.

## WaitHandle::WaitOne(int, bool) metodo


Attende che il gestore venga attivato.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) da attendere, in millisecondi; -1 significa attesa infinita, 0 significa verifica e ritorno, i valori positivi sono timeout. |
| exitContext | **bool** | Se true, l’attesa dovrebbe rilasciare il lock sul gestore prima di attendere. |

### Valore restituito

True se il gestore è stato attivato, false se il timeout è stato superato.

## Vedi anche

* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)