---
title: WaitAny()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Czeka, aż dowolny z podanych obiektów Task zakończy wykonywanie.
type: docs
weight: 183
url: /pl/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funkcja

Czeka na zakończenie wykonywania któregokolwiek z podanych obiektów [Task](../task/).

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tablica instancji [Task](../task/), na których należy czekać. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) do obserwacji podczas oczekiwania na zakończenie zadań. |

### Wartość zwracana

Indeks zakończonego zadania w tablicy zadań.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) funkcja

Czeka na zakończenie wykonywania któregokolwiek z podanych obiektów [Task](../task/).

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Tablica instancji [Task](../task/), na których należy czekać. |

### Wartość zwracana

Indeks zakończonego zadania w tablicy zadań.

## Zobacz także

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klasa [CancellationToken](../../system.threading/cancellationtoken/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)