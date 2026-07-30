---
title: ContinueWith()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una continuazione che viene eseguita quando l'attività termina.
type: docs
weight: 118
url: /it/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) metodo

Crea una continuazione che viene eseguita quando l'attività termina.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Action da eseguire quando questa attività termina |

### Valore di ritorno

TaskPtr Un nuovo task che rappresenta la continuazione

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) metodo

Crea una continuazione che viene eseguita quando l'attività termina.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TResult | Un tipo di risultato del task |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funzione per ottenere il risultato quando questa attività termina |

### Valore di ritorno

RTaskPtr Un nuovo task che rappresenta la continuazione

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [Task](../)
* Classe [Func](../../../system/func/)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Libreria [Aspose.Slides](../../../)