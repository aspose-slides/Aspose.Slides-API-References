---
title: WaitOne()
second_title: Riferimento API di Aspose.Slides per C++
description: Blocca il mutex. Esegue un'attesa illimitata se necessario.
type: docs
weight: 53
url: /it/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metodo


Blocca il mutex. Esegue un'attesa illimitata se necessario.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Valore restituito

Restituisce sempre true poiché non ritorna finché il mutex non è bloccato.

## Mutex::WaitOne(int) metodo


Blocca il mutex. Esegue un'attesa se necessario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsTimeout | int | Timeout di attesa in millisecondi. |

### Valore restituito

Restituisce true se il mutex è stato bloccato o false se il timeout è stato superato.

## Mutex::WaitOne(TimeSpan) metodo


Blocca il mutex. Esegue un'attesa se necessario.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) che rappresenta il numero di millisecondi da attendere, o un [System::TimeSpan](../../../system/timespan/) che rappresenta -1 millisecondi per attendere indefinitamente. |

### Valore restituito

Restituisce true se il mutex è stato bloccato o false se il timeout è stato superato.

## Vedi anche

* Classe [Mutex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)