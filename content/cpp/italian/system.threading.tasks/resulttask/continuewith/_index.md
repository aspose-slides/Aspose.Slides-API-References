---
title: ContinueWith()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una continuazione che viene eseguita al completamento dell'operazione di risultato.
type: docs
weight: 40
url: /it/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) metodo

Crea una continuazione che viene eseguita al completamento dell'operazione di risultato.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Azione da eseguire quando questa operazione termina, ricevendo questa operazione di risultato |

### Valore di ritorno

TaskPtr Un nuovo task che rappresenta la continuazione

## Osservazioni



L'azione di continuazione riceve questo [ResultTask](../) per accedere al valore del risultato 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) metodo


Crea una continuazione che viene eseguita al completamento dell'operazione di risultato.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


### Parametri di modello

| Parametro | Descrizione |
| --- | --- |
| TNewResult | Tipo di risultato della continuazione dell'operazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Funzione per ottenere il risultato della continuazione quando questa operazione termina, ricevendo questa operazione di risultato |

### Valore di ritorno

RTaskPtr Un nuovo task che rappresenta la continuazione

## Osservazioni



La funzione di continuazione riceve questo [ResultTask](../) per accedere al valore del risultato 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) metodo


Crea una continuazione che viene eseguita al completamento dell'operazione.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Azione da eseguire quando questa operazione termina |

### Valore di ritorno

TaskPtr Un nuovo task che rappresenta la continuazione

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) metodo


Crea una continuazione che viene eseguita al completamento dell'operazione.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


### Parametri di modello

| Parametro | Descrizione |
| --- | --- |
| TResult | Un tipo di risultato dell'operazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Funzione per ottenere il risultato quando questa operazione termina |

### Valore di ritorno

RTaskPtr Un nuovo task che rappresenta la continuazione

## Vedi anche

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultTask](../)
* Classe [Func](../../../system/func/)
* Spazio dei nomi [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)