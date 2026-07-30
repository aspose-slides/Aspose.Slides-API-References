---
title: WaitAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende che tutti gli oggetti Task forniti completino l'esecuzione.
type: docs
weight: 170
url: /it/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

Attende che tutti gli oggetti [Task](../task/) forniti completino l'esecuzione.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un array di istanze [Task](../task/) su cui attendere. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Un [CancellationToken](../../system.threading/cancellationtoken/) da osservare mentre si attende il completamento di tasks. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) function

Attende che tutti gli oggetti [Task](../task/) forniti completino l'esecuzione.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Un array di istanze [Task](../task/) su cui attendere. |

## Vedi anche

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)