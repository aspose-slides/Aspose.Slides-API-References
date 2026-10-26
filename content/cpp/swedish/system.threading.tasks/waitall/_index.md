---
title: WaitAll()
second_title: Aspose.Slides för C++ API-referens
description: Väntar på att alla tillhandahållna Task-objekt ska slutföra exekveringen.
type: docs
weight: 170
url: /sv/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funktion


Väntar på att alla tillhandahållna [Task](../task/)-objekt ska slutföra exekveringen.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | En array av [Task](../task/)-instanser att vänta på. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | En [CancellationToken](../../system.threading/cancellationtoken/) att observera medan man väntar på att uppgifterna ska slutföras. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) funktion


Väntar på att alla tillhandahållna [Task](../task/)-objekt ska slutföra exekveringen.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | En array av [Task](../task/)-instanser att vänta på. |

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klass [CancellationToken](../../system.threading/cancellationtoken/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)