---
title: Join()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce il thread gestito. Esegue un'attesa illimitata se necessario.
type: docs
weight: 196
url: /it/system.threading/thread/join/
---
## Thread::Join() metodo

Unisce il thread gestito. Esegue un'attesa illimitata se necessario.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) metodo

Unisce il thread gestito. Esegue un'attesa limitata.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| millisecondsTimeout | int | Timeout di attesa in millisecondi. |

### Valore di ritorno

True se il thread è stato unito correttamente, false se il timeout è stato superato.

## Thread::Join(TimeSpan) metodo

Unisce il thread gestito. Esegue un'attesa limitata.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [TimeSpan](../../../system/timespan/) impostato alla quantità di tempo da attendere affinché il thread termini. |

### Valore di ritorno

True se il thread è stato unito correttamente, false se il timeout è stato superato.

## Vedi anche

* Classe [Thread](../)
* Classe [TimeSpan](../../../system/timespan/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)