---
title: WaitAll()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Czeka, aż wszystkie podane obiekty Task zakończą wykonywanie.
type: docs
weight: 170
url: /pl/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funkcja


Czeka, aż wszystkie podane [Task](../task/) zakończą wykonywanie.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tablica instancji [Task](../task/), na których należy czekać. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) obserwowany podczas oczekiwania na zakończenie zadań. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) funkcja


Czeka, aż wszystkie podane [Task](../task/) zakończą wykonywanie.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tablica instancji [Task](../task/), na których należy czekać. |

## Zobacz także

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)