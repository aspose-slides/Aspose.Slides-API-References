---
title: WaitAll()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká, až všechny poskytnuté objekty Task dokončí vykonávání.
type: docs
weight: 170
url: /cs/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funkce


Čeká, až všechny poskytnuté [Task](../task/) objekty dokončí vykonávání.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Pole instancí [Task](../task/), na nichž se čeká. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/) ke sledování během čekání na dokončení úkolů. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) funkce


Čeká, až všechny poskytnuté [Task](../task/) objekty dokončí vykonávání.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Pole instancí [Task](../task/), na nichž se čeká. |

## Viz také

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Třída [CancellationToken](../../system.threading/cancellationtoken/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)