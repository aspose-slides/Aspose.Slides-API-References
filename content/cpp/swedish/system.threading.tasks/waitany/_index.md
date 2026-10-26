---
title: WaitAny()
second_title: Aspose.Slides för C++ API-referens
description: Väntar på att någon av de angivna Task-objekten ska slutföra exekveringen.
type: docs
weight: 183
url: /sv/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) funktion


Väntar på att någon av de angivna [Task](../task/)-objekten ska slutföra exekveringen.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | En array av [Task](../task/)-instanser att vänta på. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | En [CancellationToken](../../system.threading/cancellationtoken/) att observera medan du väntar på att uppgifterna ska slutföras. |

### Returvärde

Indexet för den slutförda uppgiften i arrayen av uppgifter.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) funktion


Väntar på att någon av de angivna [Task](../task/)-objekten ska slutföra exekveringen.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | En array av [Task](../task/)-instanser att vänta på. |

### Returvärde

Indexet för den slutförda uppgiften i arrayen av uppgifter.

## Se även

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Klass [CancellationToken](../../system.threading/cancellationtoken/)
* Namnrymd [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)