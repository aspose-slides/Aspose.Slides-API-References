---
title: ValueTask()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un ValueTask vuoto e non inizializzato.
type: docs
weight: 1
url: /it/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() costruttore

Costruisce un [ValueTask](../) vuoto e non inizializzato.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Osservazioni

L'attività non è completata e non contiene alcun risultato. Tentare di ottenere il risultato genererà un'eccezione. 

## ValueTask::ValueTask(const TaskPtr\&) costruttore

Costruisce un [ValueTask](../) da un puntatore condiviso a un [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | L'attività da incapsulare. Può essere null per un'attività vuota. |
## Osservazioni

Il [ValueTask](../) rappresenterà lo stato dell'attività fornita. 

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [ValueTask](../)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)