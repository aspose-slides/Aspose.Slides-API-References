---
title: WaitOne()
second_title: Riferimento API di Aspose.Slides per C++
description: Blocca il semaforo. Esegue un'attesa illimitata se necessario.
type: docs
weight: 40
url: /it/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metodo

Blocca il semaforo. Esegue un'attesa illimitata se necessario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Valore restituito

Restituisce sempre true poiché non ritorna finché il semaforo non è bloccato.

## Semaphore::WaitOne(int) metodo

Blocca il semaforo. Esegue un'attesa se necessario.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsTimeout | int | Timeout di attesa in millisecondi. |

### Valore restituito

Restituisce true se il semaforo è stato bloccato o false se il timeout è scaduto.

## Vedi anche

* Classe [Semaphore](../)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)