---
title: WhenAny()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'operazione che si completerà quando una delle operazioni fornite sarà completata.
type: docs
weight: 209
url: /it/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) funzione

Crea un'operazione che si completerà quando una delle operazioni fornite sarà completata.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | The tasks to wait on for completion. |

### Valore restituito

Un'operazione che rappresenta il completamento di una delle operazioni fornite.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) funzione

Crea un'operazione che si completerà quando una delle operazioni fornite sarà completata.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | The tasks to wait on for completion. |

### Valore restituito

Un'operazione che rappresenta il completamento di una delle operazioni fornite.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) funzione

Crea un'operazione che si completerà quando una delle operazioni fornite sarà completata.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TResult | The type of the completed task's result. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | The tasks to wait on for completion. |

### Valore restituito

Un'operazione che restituisce la prima operazione completata quando qualsiasi operazione termina.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) funzione

Crea un'operazione che si completerà quando una delle operazioni fornite sarà completata.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TResult | The type of the completed task's result. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | The tasks to wait on for completion. |

### Valore restituito

Un'operazione che restituisce la prima operazione completata quando qualsiasi operazione termina.

## Vedi anche

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Spazio dei nomi [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)