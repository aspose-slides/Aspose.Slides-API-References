---
title: WaitAny()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende che uno qualsiasi degli oggetti Task forniti completi l'esecuzione.
type: docs
weight: 183
url: /it/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funzione


Attende che uno qualsiasi degli oggetti [Task](../task/) forniti completi l'esecuzione.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un array di istanze [Task](../task/) su cui attendere. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) da osservare mentre si attende il completamento delle attività. |

### Valore di ritorno

L'indice dell'attività completata nell'array tasks.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) funzione


Attende che uno qualsiasi degli oggetti [Task](../task/) forniti completi l'esecuzione.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un array di istanze [Task](../task/) su cui attendere. |

### Valore di ritorno

L'indice dell'attività completata nell'array tasks.

## Vedi anche

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)