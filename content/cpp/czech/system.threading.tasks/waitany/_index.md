---
title: WaitAny()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká na dokončení provedení libovolného z poskytnutých objektů Task.
type: docs
weight: 183
url: /cs/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) function

Čeká na dokončení provedení libovolného z poskytnutých [Task](../task/) objektů.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Pole instancí [Task](../task/), na které se čeká. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | [CancellationToken](../../system.threading/cancellationtoken/), který se má sledovat během čekání na dokončení úkolů. |

### Návratová hodnota

Index dokončeného úkolu v poli úkolů.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) function

Čeká na dokončení provedení libovolného z poskytnutých [Task](../task/) objektů.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Pole instancí [Task](../task/), na které se čeká. |

### Návratová hodnota

Index dokončeného úkolu v poli úkolů.

## Viz také

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Třída [CancellationToken](../../system.threading/cancellationtoken/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)